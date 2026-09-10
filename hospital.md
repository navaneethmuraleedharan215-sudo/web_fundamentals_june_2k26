id   Patient_Name	Doctor_Name	  department   assigned_date   Fee
1		arun	    dr.praveen    neurology      2026-06-08    190
2		vimal	    dr.sreejith   dermatology    2026-05-08    180
3	    ajay	    dr.riswan     pediatrics     2026-05-06    150
4		ajith	    dr.vishnu     cardiology     2026-06-09    160
			


`http_request for adding new patients`
url:localhost/8000/patients/
method:POST
body"{
"patient_name":"diljith",
    "doctor_name":"dr.praveen",
    "department":"pediatrics",
    "assigned_date":2026-06-04,
    "fee":170
}


`http_request for list all patients`
url:localhost:8000/patients/
method:GET

`http_request for fetching patient detail`
url : localhost:8000/patients/4/
method:GET

`http_request for update patient`
url:localhost:8000/movie/4/
method:PUT
body"{
"patient_name":"faheem",
    "doctor_name":"dr.pradeep",
    "department":"dermatology",
    "assigned_date":2026-06-08,
    "fee":190
}


`http_request for delete patient`
url:localhost:8000/patients/4/
method:DELETE