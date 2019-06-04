# Shell Commands

|     command               |         function                                            |
|---------------------------|-------------------------------------------------------------|
|  ```cd```                 | __change directory__                                        |
|..                         | __go back__ one directory                                   |
| ```ls```                  | __list__ all files and directories in working directory     |
|```touch 'file name'```    | make __new file__ in working directory                      |
|```mkdir```                | make __new directory__                                      |
| ```-a```                  | list __all__ content                                        |
|```-l```                   | list all content in __long__ format                         |
| ```-t```                  | __order__ files and dir. by the time they were last modified|
|```-alt```                 | __combine__ '-a' '-l' and '-t'                              |
| ```*```                   | __select groups__ of files (_Wildcards_)                    |
|```mv```                   | __move files__                                              |
| ```mv 'new file name'```  | __rename files__                                            |
| ```cp```                  | __copy files__                                              |
|```rm  'file name'```      | __remove file__                                             |
|```rm -r ```               | __deletes dir__ and __all child directories__               |
|```echo 'stdin'```         | __echoes__ input back to the terminal as standard output    |
|```stdout```       | __standard output__ is printed in the terminal with ```echo```      |
|```cat```          | __output__ content of file to terminal                              |
|```>```            |__take the standard output__ of the command on the _left_,__redirect it__ to the file on the _right_ (overwright all previous content)|
|```>>```           | __takes the standard output__ of the command on the _left_ and __appends__ (_adds_) it to the file on the _right_                                         |