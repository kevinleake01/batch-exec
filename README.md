# Batch-Exec

Batch-Exec is a tool that lets you execute Unix/Linux command line programs.<br>
<br>
To get started, look at the list of templates ready for you to edit. To avoid overwriting the template, make a copy of it:<br>
<br>
cp tpl-batch-exec-10.c batch-exec-0001.c<br>
<br>
You will see something like this:<br>
<br>
/*<br>
####################################<br>
#<br>
# --- TPL-BATCH-EXEC-10.C ---<br>
#<br>
####################################<br>
*/<br>
<br>
#include <stdlib.h><br>
<br>
int main(int argc, char *argv[])<br>
{<br>
  system("");<br>
  system("");<br>
  system("");<br>
  system("");<br>
  system("");<br>
  system("");<br>
  system("");<br>
  system("");<br>
  system("");<br>
  system("");<br>
}<br>
<br>
<br>
The Templates have been written in C and C++, and the system() command from <stdlib.h> or <cstdlib> makes the connection<br>
to the Unix/Linux command line. Here are some examples:<br>
<br>
  system("ls -l\n");<br>
  system("uuidgen -t\n");<br>
  system("uuidgen -r\n");<br>
  system("echo -e \"This is a test.\\n\\n\"\n");<br>
<br>
<br>
You can now edit batch-exec-0001.c to whatever Unix/Linux commands you want to use. To run your commands, do this:<br>
<br>
  gcc batch-exec-0001.c; ./a.out<br>
<br>
<br>

