fsharpi                            (starts F# interactive)

fsharpc file.fs                    (F# compiler)

xbuild                             (builds .fsproj projects and .sln files)

mono file.exe arg1 ... argN        (runs a compiled F# program)

mkbundle --static file.exe -o file (makes a static native image, including the F# runtime)
