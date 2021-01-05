# be_test

pip install virtualenv

#once installed new environment is created in a folder


mkdir be_test
cd be_test
python -m virtualenv

#activate the virtual environment


source ./scripts/activate
or
.\scripts\activate

#install flask


pip install flask

#run the following


FLASK_APP=hello.py flask run
