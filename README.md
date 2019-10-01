# CloudCoverScriptingTest

# Script Usage
You can run this script using below methods:
  1. Providing the params as command line args
  2. Providing the params as Input 

# 1. Providing the params as command line args
# Steps:
  1. Download the zip file to you local machine
  2. Unzip the folder
  3. You shall see a dir name **CloudCoverScriptingProject** where you exracted the zip file.
  4. Navigate to the **CloudCoverScriptingProject**.
  5. Run the Main.py file using below command and command line args:
      > **python Main.py 30 cc-r ./new_image.json**
      
     where, 
     30 = Retention Days
     
     cc-r = Prefix Name to be matched
     
     ./new_image.json = Full Path to the **.json** file
  6. You shall see a list of all the objects which are due for deletion.
  7. Similary you can run the Main.py providing various values for all the 3 command line args.

# 2. Providing the params as Input
# Steps:
  1. Download the zip file to you local machine
  2. Unzip the folder
  3. You shall see a dir name **CloudCoverScriptingProject** where you exracted the zip file.
  4. Navigate to the **CloudCoverScriptingProject**.
  3. Run the Main.py file using below command:
      > **python Main.py**
  4. You shall then be promted to provide following Values:
      > **Please mention the retention days:**
      
      > **Please mention the prefix string to be matched:**
      
      > **Please mention the full path to json file:**
  5. Provide all the values and you shall get a list of all the objects which are due for deletion.
