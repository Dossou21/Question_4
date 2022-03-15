
#include <sys/types.h>
#include <md5.h>
char *
     MD5File(const char *filename, char *buf){
         return (MD5FileChunk(filename, buf, 0, 0));
     };

int main()
{
  const char *filename="file.c";
    MD5File( file.c)

}
