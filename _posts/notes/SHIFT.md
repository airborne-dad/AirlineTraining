# Cold & Dark → Before Start To the Line

1. Safety & Power On – Read & Do (this checklist flows well, easily memorizable, can speed up the process)

2. Originating/Receiving Flow & Checklist  
   a. NAV>1L NAV IDENT>6R POS INIT>3R LOAD>6R RTE>1R DEST>5R FLIGHT ID  
   b. Flow  
   c. Checklist  

3. Before Start To the Line Flow & Checklist  
   a. Flow  
      i. Datalink (DLK) Steps  
         1. Request Departure ATIS  
            a. DLK>6R ATS MENU>2L ATIS REQ>1L AIRPORT>2R DEPART>6R REQUEST*  
               i. Note wind, temp, altimeter, departure runway(s), special conditions (e.g. icing, windshear, NAVAID NOTAMs etc.)  
               ii. If applicable, enter NOTAMed NAVAIDs  
                  1. NAV>4L POS SENSORS>6L VOR/DME>6R NOTAM  
         2. Sign Fit for Duty  
            a. DLK>1L PRE FLT>1L INITIALIZE>1R SKED DAY>3L SKED TIME>4R FO PIN>6R SIGN  
         3. Request PDC  
            a. DLK>3R MSGS RCVD  
            b. 5L>SIGN RLS>4R CAPT PIN>6L ACCEPT  
            c. 3R MSGS RCVD  
               i. Compare filed route (page 1) with cleared route (page 2) and note differences if any  
               ii. Bug  
                  1. Runway heading for now  
                  2. Initial cleared alt.  
               iv. See page 3 for squawk code, then enter it  
                  1. RADIO>5R XPDR1  

4. *Setup FD Pro - may accomplish at any point*  
   a. Build route (use Import if applicable)  
   b. Compile charts (-7s, SID, STAR, -9s etc.)

5. Request T/O Data  
   a. DLK>4R RWY PERF/W&B>1L TAKEOFF CONDITIONS  
      i. Fill out everything on page 1 but 3R PTOW  
      ii. Fill out everything on page 2 but 1L FLAP  
   b. On page 1, 4R W&B LOADSHEET  
      i. Complete page 1  
      ii. Page 2 change Mode to Auto  
      iii. On page 1, 6R SEND  
   ii. Flight Plan (FPL) Steps  
      1. Build Flight Plan  
         a. Enter the flight plan  
            i. Enter destination on the right and copy & paste it to the left to close the flight plan  
            ii. Start with 6L DEPARTURE, select runway & SID  
            iii. Set 6L DEP APP (3000 & 6)  
            iv. Enter arrival, NAV>6R ARRIVAL, select arrival  
            v. Enter route  
            vi. Verify route  
            vii. Activate (this will auto sequence PERF INIT on 6R)  
         b. PERF INIT  
            i. Fill out all 3 pages but 4L ZFW on page 3  
   b. To the Line Checklist  

---

# Before Start Below the Line → Before Takeoff

1. Before Start Below the Line Flow & Checklist  
   a. Flow  
   b. Checklist  

2. After Start Flow & Checklist  
   a. Load FMS T/O data (when available)  
      i. MCDU 1 → DLK>4R RWY PERF/W&B>3L TAKEOFF RWY DATA  
         1. Note ZFW on 5R ZFW/CG  
      ii. MCDU 2 → PERF>1L PERF INIT  
         1. Page 3, enter ZFW on 4l ZFW  
      iii. MCDU 2 → PERF>2R TAKEOFF  
         1. Transfer ACARS landing data on MCDU 1 page 3 to page 3 here  
         2. Transfer ACARS landing data on MCDU 1 page 3 to TRS (will auto sequence from 6R T.O. Data)  
            a. TRS>6R TO DATASET>2R REF ECS>3R REF A/I>4R TO TEMP>4R FLEX T/O>5R FLEX TEMP  

3. Taxi Flow & Checklist  
   a. Flow  
   b. Checklist  

4. Before Takeoff Flow & Checklist  
   a. Flow  
   b. Checklist  

---

# Approach Setup/Briefing

1. PM Approach Setup & Briefing Flow – Do this early on as PM (prior to 200nm mark – check PROG), hopefully before PF does their flow, which is approach brief, but the PF can assign PM to do it.  
   a. Arrival ATIS  
   b. Build approach & arrival procs (NAV>6R ARRIVAL)  
      i. RUNWAY, APPROACH, STAR etc.  
      ii. Verify on FPL alt. and speed limits  
      iii. Manual tune ILS freq (PROG, both sides)  
      iv. Bug Course (PREV), min alt (BARO, unless CAT II then RA)  
   c. Find Gross Weight  
      i. PERF>1R PERF DATA  
   d. Request landing data  
      i. DLK>4R>1R and put in LDW which is the gross weight from last step  
      ii. Send it in  
   e. ONCE received it (on page 3), enter it in PERF  
      i. PERF>4R LANDING  
         1. Page 1, RWY OAT & LANDING FLAP  
         2. Page 2, V speeds  
         3. Note the auto brake distances and set the settings as desired  
   f. Brief approach if assigned by the PF  

2. Descent Flow & Checklist  

3. Descending 10,000’ft Flow  

4. Landing Flow & Checklist  
