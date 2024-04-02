   1  ls
    2  cd folder
    3  whoami
    4  sudo chown root upper.txt
    5  ls -l
    6  cat lower.txt
    7  chmod 775 upper.txt
    8  sudo chmod 775 upper.txt
    9  ls -l
   10  cat lower.txt
   11  upper.txt
   12  ls
   13  ls -l
   14  cat upper.txt
   15  cat lower.txt
   16  chmod 777 upper.txt
   17  sudo chmod 777 upper.txt
   18  find . -p 777
   19  find . -perm 777
   20  find . -type f -name "*.txt"
   21  find . -type f -name "*.txt" -exec rm -rf {} +
   22  touch name.txt
   23  touch surname.txt
   24  touch companies.txt
   25  df  name.txt names.txt
   26  mv  name.txt names.txt
   27  mv  surname.txt surnames.txt
   28  vi names.txt
   29  vi companies.txt
   30  grep -V
   31  grep "Kunal" names.txt
   32  grep "Harry" names.txt
   33  grep "harry" names.txt
   34  grep "patric" names.txt
   35  vi names.txt
   36  grep "parker" names.txt
   37  grep "Gadidala" names.txt
   38  grep -w "Sivaji" names.txt
   39  grep -w -i  "Sivaji" names.txt
   40  grep -w -i  "Siva" names.txt
   41  grep  -i  "Siva" names.txt
   42  grep -n "kunal" names.txt
   43  grep -n "foggle" names.txt
   44  grep -win "Charlie" names.txt
   45  grep -A 2 "sivaji" names.txt
   46  grep -B 2 "jim" names.txt
   47  grep -B 4  "jim" names.txt
   48  grep -B 4  "jim" ./ .txt
   49  grep -win "peter" ./*.txt
   50  grep -wirl "sivaji" .
   51  history