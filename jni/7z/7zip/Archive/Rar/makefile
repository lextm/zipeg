PROG=../../../bin/Formats/Rar.so

LOCAL_FLAGS=

include ../../../makefile.machine

LOCAL_SHARED=$(LINK_SHARED)
LIBS=$(LOCAL_LIBS_DLL)

MY_WINDOWS= \
	$(MY_HOME)/myModuleFileName.o \
	$(MY_HOME)/wine_date_and_time.o

OBJS = \
../../../Common/MyWindows.o \
../../../Common/Alloc.o\
../../../Common/Vector.o\
../../../Common/StringConvert.o\
../../../Common/String.o\
../../../Common/CRC.o\
../../../Common/IntToString.o\
../../../Common/UTFConvert.o\
CodecsPath.o\
FilterCoder.o\
ItemNameUtils.o \
InStreamWithCRC.o\
OutStreamWithCRC.o\
DLL.o\
FileFind.o\
PropVariant.o\
Synchronization.o\
CopyCoder.o\
RarHandler.o\
RarHeader.o\
RarIn.o\
RarItem.o\
RarVolumeInStream.o\
RarAES.o\
Rar20Cipher.o\
Rar20Crypto.o\
LimitedStreams.o\
ProgressUtils.o\
StreamObjects.o\
StreamUtils.o\
7zMethodID.o\
7zMethods.o \
Sha1.o

include ../../../makefile.glb

