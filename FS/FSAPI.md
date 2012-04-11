FS API
======

public:

handle open(path)
void close(handle)

read(handle, buf, pos, amount)
write(handle, buf, pos, amount)

addfile(path)
rmfile(path)

adddir(path)
rmdir(path)

private:

-------

mkfs.hat:

disksize = 51200
blocksize = 256

header = 16

16 inodes+blocks = 2 + 16*16 + 256*16 = 4354

disksize - header = 51184

num_inodes = 176
num_blocks = 176

header start = 0
inodemapstart = 16
blockmapstart = inodemapstart + 176/16 = inodemapstart + 11 = 27
inodestart = blockmapstart + 176/16 = blockmapstart + 11 = 38
blockstart = inodestart + numinodes*16 = 2816

get header checksum
write header

write root inode
write root block

done.

