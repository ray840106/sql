node建立：
countrie.csv--國家資訊;department.csv--部門資訊;employee.csv--員工資訊;
job.csv--工作資訊;location.csv--地址資訊;region.csv--區域資訊;
relationship建立：
cou_reg.csv--國家與區域關係;dep_loc.csv--部門與地址關係;dep_man.csv--部門與主管關係;emp_dep.csv--員工與部門關係;
emp_job.csv--員工與工作關係;emp_man.csv--員工與主管關係;loc_cou.csv--地址與國家關係;

countrie.csv
  COUNTRY:ID, COUNTRY_NAME,             :LABEL
1	CA	        Canada	                  country
2	DE	        Germany	                  country
3	UK	        United Kingdom	          country
4	US	        United States of America	country

department.csv
  DEPARTMENT:ID,  DEPARTMENT_NAME,  :LABEL
1	70	            Public Relations	department
2	10	            Administration	  department
3	20	            Marketing	        department
4	50	            Shipping	        department
5	60	            IT	              department
6	80	            Sales	            department
7	90	            Executive	        department
8	110	            Accounting	      department
9	190	            Contracting      	department

employee.csv
    EMPLOYEE:ID, FIRST_NAME, LAST_NAME, EMAIL,    PHONE_NUMBER,         HIRE_DATE , SALARY  , COMMISSION_PCT,:LABEL
1	  100	         Steven	     King	      SKING	    515.123.4567	        17-Jun-87	  24000	    NA	            employee
2	  101        	 Neena	     Kochhar	  NKOCHHAR	515.123.4568	        21-Sep-89	  9900	    NA	            employee
3	  102	         Lex	       De Haan	  LDEHANN	  515.123.4569	        13-Jan-93	  9900   	  NA	            employee
4	  103	         Alexander	 Hunold	    AHUNOLD	  590.423.4567	        3-Jan-90	  9900      NA	            employee
5	  104	         Bruce	     Ernst	    BERNST	  590.423.4568	        21-May-91	  6600	    NA	            employee
6	  107	         Diana	     Lorentz	  DLORENTZ	590.423.5567	        7-Feb-99	  4620	    NA	            employee
7	  124	         Kevin	     Mourgos	  KMOURGOS	650.123.5234	        16-Nov-99	  5800	    NA	            employee
8	  141	         Trenna	     Rajs	      TRAJS	    650.121.8009	        17-Oct-95	  3500	    NA	            employee
9	  142	         Curtis	     Davies	    CDAVIES	  650.121.2994	        29-Jan-97	  3100	    NA	            employee
10	143	         Randall	   Matos	    RMATOS	  650.121.2874	        15-Mar-98	  2600	    NA	            employee
11	144	         Peter	     Vargas	    PVARGAS	  650.121.2004	        9-Jul-98	  2500	    NA	            employee
12	149          Eleni	     Zlotkey	  EZLOTKEY	011.44.1344.429018	  29-Jan-00	  10500	    0.20	          employee
13	174	         Ellen	     Abel	      EABEL	    011.44.1644.429267	  11-May-96	  11000	    0.30	          employee
14	176	         Jonathon	   Taylor	    JTAYLOR	  011.44.1644.429265	  24-Mar-98	  8600	    0.20	          employee
15	178	         Kimberley	 Grant	    KGRANT	  011.44.1644.429263	  24-May-99	  7000	    0.15	          employee
16	200	         Jennefer	   Whalen	    JWHALEN	  515.123.4444	        17-Sep-87	  4400	    NA	            employee
17	201	         Michael	   Hartstein	MHARTSTE	515.123.5555	        17-Feb-96	  14300	    NA	            employee
18	202	         Pat	       Fay	      PFAY	    603.123.6666	        17-Aug-97	  6600	    NA	            employee
19	205	         Shelley	   Higgins	  SHIGGINS	515.123.8080	        7-Jun-94	  12000	    NA	            employee
20	206	         William	   Gietz	    WGIETZ	  515.123.8181	        7-Jun-94	  8300	    NA	            employee

job.csv
    JOB:ID,     JOB_TITLE,                    MIN_SALARY, MAX_SALARY, :LABEL
1	  AD_PRES	    President	                    20000	      40000	      job
2	  AD_VP	      Administration Vice President	15000	      30000	      job
3	  AD_ASST	    Administration Assistant	    3000	      6000	      job
4	  AC_MGR	    Accounting Manager	          8200	      16000	      job
5	  AC_ACCOUNT	Public Accountant	            4200	      9000	      job
6	  SA_MAN	    Sales Manager	                10000	      20000	      job
7	  SA_REP	    Sales Representative	        6000	      12000	      job
8	  ST_MAN	    Stock Manager	                5500	      8500	      job
9	  ST_CLERK	  Stock Clerk	                  2000	      5000	      job
10	IT_PROG	    Programmer	                  4000	      10000	      job
11	MK_MAN	    Marketing Manager	            9000	      15000	      job
12	MK_REP	    Marketing Representative	    4000	      9000	      job

location.csv
  LOCATION:ID,  STREET_ADDRESS,                           POSTAL_CODE,    CITY,               STATE_PROVINCE,       :LABEL
1	1400	        2014 Jabberwocky Rd	                      26192	          Southlake	          Texas	                location
2	1500	        2011 Interiors Blvd	                      99236	          South San Fransisco	California	          location
3	1700	        2004 Charade Rd	                          98199	          Seattle	            Washington	          location
4	1800	        460 Bloor St. W.	                        ON M5S 1XB	    Toronto	            Ontario	              location
5	2500	        Magdalen Centre, The Oxford Science Park	OX9 9ZB	        Oxford	            Oxford	              location

region.csv
  REGION:ID,  REGION_NAME,            :LABEL
1	1	          Europe	                region
2	2	          Americas	              region
3	3	          Asia	                  region
4	4	          Middle East and Africa	region

