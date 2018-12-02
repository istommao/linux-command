# 压缩与打包

- *.Z compress
- *.zip   zip
- *.gz    gzip
- *.bz2   bzip2
- *.xz    xz
- *.tar   tar 程序打包的数据，没有经过压缩
- *.tar.gz    tar 程序打包的文件，经过 gzip 的压缩
- *.tar.bz2   tar 程序打包的文件，经过 bzip2 的压缩
- *.tar.xz    tar 程序打包的文件，经过 xz 的压缩

## .tar

```bash
tar cvf folder.tar folder

tar xvf folder.tar
```

## .tar.bz2

```bash
tar -jxvf *.tar.bz2
```

## tar.xz

```bash
xz -d *.tar.xz
```

## .tar.gz

```bash
tar zcvf *.tar.gz folder

tar zxvf *.tar.gz
```

## tar.bz2

```bash
tar jcvf *.tar.bz2 folder

tar jxvf *.tar.bz2
```

## tar.bz

```bash
tar jxvf *.tar.bz
```
