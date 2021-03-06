# PharmaCat

* Run on Python 3.5

The PharmaCat Project is divided into **2 sections**:

*To setup the Web Application along with API server do:*
```
pip install virtualenv
virtualenv venv
venv\scripts\activate
```
**Then after activating the virtual environment do:**
```
pip install -r requirements.txt
```

**Documentation for PharmaCat RESTFUL JSON API**


| Method | URL                                                                | USE                                                     |
| ------ | ------------------------------------------------------------------ | ------------------------------------------------------- |
|  `GET` | http://127.0.0.1:5000/api/details/<b>apitoken</b>                  | Shows your PharmaCat Account Details                    |
|  `GET` | http://127.0.0.1:5000/api/login/<b>username~password</b>           | Generates your PharmaCat API Token upon successful login|
|  `GET` | http://127.0.0.1:5000/api/symptoms                                 | Generates list of all Symptoms in your Database         |
|  `GET` | http://127.0.0.1:5000/api/diagnosesym/<b>symptom1~symptom2</b>    | Diagnoses Disease,Medicine and Specialist               |
|  `GET` | http://127.0.0.1:5000/api/diagnosetext/<b>word1 ~ word2 ~ word3</b>    | Diagnoses Disease                                       |
|  `GET` | http://127.0.0.1:5000/api/hospital/<b>apitoken</b>                 | Generates list of Hospitals near you                      |
|  `GET` | http://127.0.0.1:5000/api/register/<b>username ~ password ~ email ~ fullname ~ address ~ bloodgroup ~ age</b>                 | Registers the Patient in the PharmaCat Database                      |

