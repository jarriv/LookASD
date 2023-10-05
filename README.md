# LookASD
System to assist in the detection of ASD. Focused on children aged 5 to 12 years old.

# How to install lookASD

* The commands below are based on Debian/Ubuntu-based Linux distributions:

* Run the following commands:

  sudo apt-get install spyder python3-pip python3-flask
  pip install numpy pandas fpdf scikit-learn flask flask-mail flask-jsglue pyopenssl

* Lower the SSL security level.

* In the file ../Flask_17_08_2023/Projeto.py, adjust the parameters below:

  fromaddr = "@.edu.br" --> Adjust the sender's email address.
  
  s = smtplib.SMTP('smtp.***.edu.br', 587) --> Adjust the SMTP server's name.
  
  s.login(fromaddr, base64.b64decode("**********").decode("utf-8")) --> Adjust the email password.
