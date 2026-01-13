Just another playing around Bluepill kind of experiment, but I thought it had the potential to be a standalone repository. 

Files namely "W25Q32.h" and "W25Q32.c" play the main role here. Used Winbond SPI W25Q flash series.
It has the features to erase a sector, write to a page and read from anywhere.Pretty much everything you could do with a flash memory. But can be modified to work or run efficiently.

The code could be used for any sized winbond flash without any modification. Because the page size, sector size and block size do not change. But the number of them changes as memory size changes

Do not believe the memory size printed on the flash device. Read the 24 bit JEDEC ID and check the last 8 bits to know the size.

Anyways, if you're interested, you can make it better, and I am open to learn. But I just did it seperately, so I can integrate it in another project where simple driver was enough.

##Author
Jagakishan S.K

