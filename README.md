# SSHW2
//Michael Said
//Liam May
//SSHW2

//Not too much going on so far just opening a file and then printing it out


char inputFile[100000];
FILE *fp;
fopen("nameoftext.txt", "r");

while(!feof(fp)){

  fgets(inputFile, 100000 , fp);
  
  //thinking we'll need an if condition on the puts because he doesnt want to see comments
  //so maybe if index 0 != '/' && index 1 != '/'
  puts(inputFile);

}
  
  return 0;
}
