# LookASD
System to assist in the detection of ASD. Focused on children aged 5 to 12 years old.

# How to install lookASD

* The commands below are based on Debian/Ubuntu-based Linux distributions:

* Run the following commands:

  sudo apt-get install spyder python3-pip python3-flask
  
  pip install numpy pandas fpdf scikit-learn flask flask-mail flask-jsglue pyopenssl

* Lower the SSL security level.

* In the file ../Projeto.py, adjust the parameters below:

  fromaddr = "@.edu.br" --> Adjust the sender's email address.
  
  s = smtplib.SMTP('smtp.***.edu.br', 587) --> Adjust the SMTP server's name.
  
  s.login(fromaddr, base64.b64decode("**********").decode("utf-8")) --> Adjust the email password.


* [Article link](https://github.com/jarriv/LookASD/blob/c37a6b65bbf5e5b2ad97640f34ad14a49cd64555/lookASD.pdf)

* [License](https://github.com/jarriv/LookASD/blob/main/License.txt)

* [AGPL3](https://www.gnu.org/licenses/agpl-3.0.html)

* [Presentation - In Portuguese](https://docs.google.com/presentation/d/1oRCSX1-4y10AIzFwhVMhHq00ULVidFYwhJfYXLb43Wo/edit?usp=sharing)
