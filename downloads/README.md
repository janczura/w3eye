# Downloads

Drop the release `.exe` here, named exactly:

    w3eye-windows-x86_64.exe

The landing page links to `/downloads/w3eye-windows-x86_64.exe`.

After building on Windows:

    w3eye> cargo build --release --target x86_64-pc-windows-msvc
    cp target/x86_64-pc-windows-msvc/release/w3eye.exe \
        ../w3eye-web/downloads/w3eye-windows-x86_64.exe

Then publish the file's SHA-256 on the landing page's download section (sha256sum downloads/w3eye-windows-x86_64.exe).
