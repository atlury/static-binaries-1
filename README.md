# static-binaries
Static binaries for common tools


# Software list
| Software        | VERSION    | Binary Sample | PseudoLink |
| :-------------- | :--------: | :------- | :--------: |
| e2fsprogs       | 1.45.5     | e2fsck   | [.tar.xz](https://mirrors.edge.kernel.org/pub/linux/kernel/people/tytso/e2fsprogs/v${VERSION}/e2fsprogs-${VERSION}.tar.xz)  |
| nano            | 4.7        | nano     | [.tar.xz](https://www.nano-editor.org/dist/v4/nano-${VERSION}.tar.xz)  |
| squashfs        | 4.4        | mksquashfs     | [.tar.gz](https://github.com/plougher/squashfs-tools/archive/${VERSION}.tar.gz)  |
| wget            | 1.20.3     | wget     | [.tar.gz](https://ftp.gnu.org/gnu/wget/wget-${VERSION}.tar.gz)  |
| p7zip           | 16.02      | 7za      | [.tar.gz](https://github.com/btolab/p7zip/archive/${VERSION}.tar.gz)  |
| ncdu            | 1.14.1     | ncdu     | [.tar.gz](https://dev.yorhel.nl/download/ncdu-${VERSION}.tar.gz)  |
| ddrescue        | 1.24       | ddrescue | [.tar.lz](https://mirror.cyberbits.eu/gnu/ddrescue/ddrescue-${VERSION}.tar.lz)  |
| file            | 5.38       | file     | [.tar.lz](ftp://ftp.astron.com/pub/file/file-${VERSION}.tar.gz)  |

# Build
If you want to build the binaries by yourself, just execute:

```bash
build/build.sh
```

