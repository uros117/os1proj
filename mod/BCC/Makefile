SRC = ..\*.cpp 
INCLUDES = ..\INCLUDE\*.h 
LIBS = ..\LIB\*.lib 
INCLUDEPATH = C:/bc31\include;..\INCLUDE;
LIBSPATH = C:/bc31\lib;..\LIB;
TARGET = mod.exe
$(TARGET):	$(SRC) $(INCLUDES) configuration.xmi
	bcc.exe -mh -v -e$(TARGET) -I$(INCLUDEPATH) -L$(LIBSPATH) $(SRC) $(LIBS)
all:	$(TARGET)
clean:
	-del *.obj
	-del $(TARGET)
	-del *.asm
configuration.xmi:	
	configuration.xmi