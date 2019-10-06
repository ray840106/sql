node建立：
countrie.csv--國家資訊;department.csv--部門資訊;employee.csv--員工資訊;
job.csv--工作資訊;location.csv--地址資訊;region.csv--區域資訊;
relationship建立：
cou_reg.csv--國家與區域關係;dep_loc.csv--部門與地址關係;dep_man.csv--部門與主管關係;emp_dep.csv--員工與部門關係;
emp_job.csv--員工與工作關係;emp_man.csv--員工與主管關係;loc_cou.csv--地址與國家關係;

countrie.csv
  COUNTRY:ID,COUNTRY_NAME,:LABEL
	CA	        Canada	                  country


department.csv
  DEPARTMENT:ID,  DEPARTMENT_NAME,  :LABEL
	70	            Public Relations	department


employee.csv
    EMPLOYEE:ID, FIRST_NAME, LAST_NAME, EMAIL,    PHONE_NUMBER,         HIRE_DATE , SALARY  , COMMISSION_PCT,:LABEL
	  100	         Steven	     King	      SKING	    515.123.4567	        17-Jun-87	  24000	    NA	            employee


job.csv
    JOB:ID,     JOB_TITLE,                    MIN_SALARY, MAX_SALARY, :LABEL
	  AD_PRES	    President	                    20000	      40000	      job


location.csv
  LOCATION:ID,  STREET_ADDRESS,                           POSTAL_CODE,    CITY,               STATE_PROVINCE,       :LABEL
	1400	        2014 Jabberwocky Rd	                      26192	          Southlake	          Texas	                location


region.csv
  REGION:ID,  REGION_NAME,            :LABEL
	1	          Europe	                region


