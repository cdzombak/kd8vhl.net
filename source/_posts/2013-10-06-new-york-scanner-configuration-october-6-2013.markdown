---
layout: post
title: "New York Scanner Configuration, October 6 2013"
date: 2013-10-06 17:54
comments: false
categories: Scanning, BC75XLT
---

Having [recently moved](http://chris.dzombak.name/blog/2013/08/my-next-step.html) to NYC, I sat down today and updated my ([BC75XLT](http://www.amazon.com/gp/product/B00A1VSO9M/ref=as_li_ss_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=B00A1VSO9M&linkCode=as2&tag=cdzombak-20) configuration for the city. I'm living in Brooklyn and working in Manhattan, so some of the choices I made below will need some tweaking if you live/work in another borough.

*You can download this configuration [here](/files/NYC_cdzombak_2013-10-06.bc75xlt_ss). See also my [notes on programming and using the BC75XLT](/blog/2013/10/programming-and-using-the-bc75xlt/).*

Note that there are some "TODO" notes to myself embedded throughout this document. The stuff I still need to do is listed on my [todo page](/todo.html).

References: see [AirNav](http://www.airnav.com/) and the NY [VFR chart](http://vfrmap.com/) for air information. [RadioReference](http://www.radioreference.com/apps/db/?ctid=1855) for NYC frequencies and for additional info on [LGA](http://www.radioreference.com/apps/db/?aid=1172), [JFK](http://www.radioreference.com/apps/db/?aid=1171), [EWR](http://www.radioreference.com/apps/db/?aid=1170).

## 1. Ham

*TODO: complete this after I have my HT set up*

## 2. 2m Simplex (& Additional Ham)

*TODO: complete this after I get my HT set up*

*offset: +30*

031. 146.43
032. 146.46
033. 146.49
034. 146.52 (calling frequency; priority)
035. 146.55
036. 146.58
037. 147.42
038. 147.45
039. 147.48
040. 147.51
041. 147.54
042. 147.57

## 3. Aviation - LGA & JFK

**Note:** ATIS frequencies are not included in this scanner plan. Get ATIS via ForeFlight, telephone, or tune in specifically with your scanner or aviation transceiver.

**Note:** due to lack of space, airline-specific and ground frequencies are not included in this plan. For reference:

* LGA Ground 127.675
* LGA Ground 121.7
* LGA Ground 121.85
* JFK Ground 121.65
* JFK Ground 121.9

**Note:** due to lack of space, EWR is not included in this plan.

*offset: +60*

061. Emergency 121.5 (priority)
062. LGA & JFK UNICOM 122.95

### LGA

*offset: +62*

063. NY Approach 120.8
064. NY Appr (secondary) 118.0
065. NY Appr (secondary) 124.95
066. NY Appr (secondary) 127.3
067. NY Appr (secondary) FINAL 128.8
068. NY Appr (secondary) 132.7
069. NY Clearance Delivery 135.2
070. NY Clearance Delivery (helicopter) 121.875
071. NY Departure 120.4
072. NY Dep (secondary) 124.45
073. NY Dep (secondary) 127.05
074. Taxi 135.2 (TODO: DUPE of 069)
075. Tower 118.7

### JFK

*offset: +75*

076. Taxi 135.05
077. Tower (runways 04R/22L & 13L/31R) 119.1
078. Tower (runways 04L/22R & 13R/31L) 123.9
079. NY Approach 127.4
080. NY Appr (secondary) 109.5
081. NY Appr (secondary) 118.4
082. NY Appr (secondary) 123.7
083. NY Appr (secondary) 126.8
084. NY Appr (secondary) 132.4
085. NY Appr (secondary) 134.35
086. NY Clearance Delivery 135.05 (TODO: DUPE of 076)
087. NY Departure 135.9
088. NY Dep (secondary) 123.7 (TODO: DUPE of 082)
089. NY Dep (secondary) 124.75
090. NY Dep (secondary) 134.35 (TODO: DUPE of 085)

## 4. Aviation - Small airports and heliports

**Note:** FSS (122.2) is not included in this plan.

*offset: +90*

091. Emergency 121.5 (priority)
092. New York Skyports 6N7 122.9
093. KJRB (Downtown Manhattan; heliport) CTAF/UNICOM; West 30th St (heliport) CTAF/UNICOM 123.05
094. East 34th St 6N5 CTAF/UNICOM (heliport) 123.075
095. FRG/ISP UNICOM 122.95 (TODO: DUPE of )

### Republic (KFRG)

*offset: +95*

096. CTAF/Tower 118.8
097. Ground 121.6
098. Tower (secondary) 125.2
099. NY Approach 127.4 (TODO: DUPE of )
100. NY Appr (secondary) 118.4 (TODO: DUPE of 081)
101. NY Appr/Dep (secondary) 123.7 (TODO: DUPE of 081/088)
102. NY Appr (secondary) 132.4 (TODO: DUPE of 084)
103. NY Appr/Dep (secondary) 134.35 (TODO: DUPE of 085, 090)
104. NY Clearance Delivery 128.25
105. NY Departure 125.7

### KISP

*offset: +105*

106. Tower/CTAF 119.3
107. Ground 135.3
108. Tower (secondary) 124.3
109. NY Approach 118.0 (TODO: DUPE of 064)
110. NY Clearance Delivery 121.85
111. NY Departure 118.0 (TODO: DUPE of 064/109)

### KTEB

*offset: +111*

112. Ground 121.9
113. Tower 119.5
114. Tower (secondary) 125.1
115. NY Approach 127.6
116. NY Clearance Delivery 128.05
117. NY Departure 126.7
118. NY Dep (secondary) 119.2

### Linden

**Note:** due to space limitations, Clearance Delivery 128.35 is not included in this plan.

*offset: +118*

119. CTAF/UNICOM 123.0
120. NY Approach 135.35

## 5. Police

*offset: +120*

### Brooklyn

121. 476.46250  WIF557  RM  110.9 PL    BK 60/61    Precincts 60, 61 Law Dispatch
122. 476.51250  WIF580  RM  123.0 PL    BK 62/68    Precincts 62, 68 Law Dispatch
123. 476.93750  WIF574  RM  136.5 PL    BK 63/69    Precincts 63, 69 Law Dispatch
124. 476.86250  WIF551  RM  151.4 PL    BK 66/70    Precincts 66, 70 Law Dispatch
125. 477.01250  WIF581  RM  167.9 PL    BK 67/71    Precincts 67, 71 Law Dispatch
126. 476.41250  WIF555  RM  186.2 PL    BK 72/76/78 Precincts 72, 76, 78 Law Dispatch
127. 476.98750  WIF553  RM  100.0 PL    BK 73/75    Precincts 73, 75 Law Dispatch
128. 476.73750  WIF540  RM  110.9 PL    BK 77/79    Precincts 77, 79 Law Dispatch
129. 476.78750  WIF554  RM  123.0 PL    BK 81/83    Precincts 81, 83 Law Dispatch
130. 476.76250  WIF556  RM  136.5 PL    BK 84/88    Precincts 84,88 Law Dispatch
131. 476.68750  WIF546  RM  151.4 PL    BK 90/94    Precincts 90, 94 Law Dispatch
132. 470.98750  WIK933  RM  136.5 PL    BK PBBK Patrol Boro Brooklyn Law Dispatch
133. 470.96250  WIK928  RM  047 DPL BK Transit  Transit Brooklyn

### Manhattan

*offset: +133*

134. 476.56250  WIF549  RM  100.0 PL    M 1/5/7 Precincts 1, 5, 7   FM  Law Dispatch
135. 476.43750  WIF575  RM  110.9 PL    M 6/9   Precincts 6, 9  FM  Law Dispatch
136. 476.33750  WIF548  RM  123.0 PL    M 10/13 Precincts 10, 13    FM  Law Dispatch
137. 476.58750  WIF542  RM  136.5 PL    M 17/MTx    Precincts MTS, 17, MTN  FM  Law Dispatch
138. 476.38750  WIF576  RM  151.4 PL    M 19/23 Precincts 19, 23    FM  Law Dispatch
139. 476.31250  WIF539  RM  167.9 PL    M 20/CPP/24 Precincts 20, CPk, 24   FM  Law Dispatch
140. 476.63750  WIF537  RM  186.2 PL    M 25/28/32  Precincts 25, 28, 32    FM  Law Dispatch
141. 476.36250  WIF538  RM  100.0 PL    M 26/30 Precincts 26, 30    FM  Law Dispatch
142. 476.88750  WIF541  RM  110.9 PL    M 33/34 Precincts 33, 34    FM  Law Dispatch
143. 471.06250  WIF568  RM  110.9 PL    MN PBMN Patrol Boro Manhattan   FM  Law Dispatch
144. 471.08750  WIH585  RM  025 DPL MN Transit  Transit Manhattan   FM  Law Dispatch

### Citywide

*offset: +144*

145. 460.48750  WPBQ332     M   241.8 PL    TAC U   Inter-Agency TAC    FM  Law Tac
146. 485.53750  WIM507  M   233.6 PL    TAC V   Communications Div., Fleet Services     FM  Law Tac
147. 458.82500  KSI296  M   225.7 PL    TAC W   Special Commands (HQ Security)  FM  Law Tac

## 6. Police Citywide

*offset: +150*

151. 470.68750  WIK936  RM  100.0 PL    CW 1    Citywide 1  FM  Law Dispatch
152. 470.71250  WIK929  RM  110.9 PL    CW 2    Citywide 2  FM  Law Dispatch
153. 470.86250  WIF562  RM  151.4 PL    CW 3    Citywide 3  FM  Law Dispatch
154. 470.83750  WIF567  RM  136.5 PL    SOD Special Operations Division     FM  Law Dispatch
155. 470.81250  WIF559  RM  123.0 PL    Traffic Traffic Division (Highway Units)    FM  Law Dispatch
156. 470.73750  WIF565  RM  186.2 PL    DET 1   Detective 1     FM  Law Tac
157. 470.63750  WIF561  RM  136.5 PL    DET 2   Detective 2     FM  Law Tac
158. 470.66250  WIF564  RM  167.9 PL    SPIN    Special Investigations  FM  Law Tac
159. 470.78750  WIK934  RM  100.0 PL    OCCB 1  Organized Crime Control Bureau 1    FM  Law Tac
160. 471.01250  WIF569  RM  167.9 PL    OCCB 2  Organized Crime Control Bureau 2    FM  Law Tac
161. 471.11250  WIF536  RM  110.9 PL    CDCW    Communications Div., Fleet Services     FM  Law Tac
162. 485.61250  WIM658  M   203.5 PL    TAC A   TAC A   FM  Law Tac
163. 485.58750  WIM660  M   210.7 PL    TAC B   TAC B   FM  Law Tac
164. 485.56250  WIM664  M   218.1 PL    TAC C   TAC C   FM  Law Tac
165. 485.48750  WIM511  M   225.7 PL    TAC D   TAC D   FM  Law Tac
166. 485.46250  WIM527  M   233.6 PL    TAC E   TAC E   FM  Law Tac
167. 485.43750  WIM515  M   203.5 PL    TAC F   Task Force, Housing Bureau  FM  Law Tac
168. 473.68750  WIK936  M   210.7 PL    TAC G   Special Operations Division and Traffic     FM  Law Tac
169. 473.71250  WIK929  M   218.1 PL    TAC H   Special Operations Division and Traffic     FM  Law Tac
170. 465.11250  WPBQ332     M   203.5 PL    TAC J   TAC J   FM  Law Tac
171. 465.18750  WPBQ332     M   210.7 PL    TAC K   TAC K   FM  Law Tac
172. 465.23750  WPBQ332     M   218.1 PL    TAC L   TAC L   FM  Law Tac
173. 465.31250  WPBQ332     M   225.7 PL    TAC M   TAC M   FM  Law Tac
174. 465.46250  WPBQ332     M   233.6 PL    TAC N   TAC N   FM  Law Tac
175. 465.48750  WPBQ332     M   241.8 PL    TAC O   TAC O   FM  Law Tac
176. 460.11250  WPBQ332     M   203.5 PL    TAC P   TAC P   FM  Law Tac
177. 460.18750  WPBQ332     M   210.7 PL    TAC Q   TAC Q   FM  Law Tac
178. 460.23750  WPBQ332     M   218.1 PL    TAC R   TAC R   FM  Law Tac
179. 460.31250  WPBQ332     M   225.7 PL    TAC S   TAC S   FM  Law Tac
180. 460.46250  WPBQ332     M   233.6 PL    TAC T   TAC T   FM  Law Tac

## 7. Fire Dispatch

*offset: +180*

181. 482.00625  WQFH239     B   131.8 PL    BX Disp Bronx Dispatch  FMN     Fire Dispatch
182. 482.01875  WQFH239     B   136.5 PL    BK Disp Brooklyn Dispatch   FMN     Fire Dispatch
183. 482.10625  WQFH238     B   146.2 PL    MN Disp Manhattan Dispatch  FMN     Fire Dispatch
184. 482.03125  WQFH239     B   141.3 PL    QN Disp Queens Dispatch     FMN     Fire Dispatch
185. 482.04375  WQFH238     B   151.4 PL    SI Disp Staten Island Dispatch  FMN     Fire Dispatch
186. 482.23125  WQFH238     B   131.8 PL    CW1 Disp    Citywide 1 Dispatch     FMN     Fire Dispatch
187. 483.38125  WQFH238     B   167.9 PL    CW2 Disp    Citywide 2 Dispatch     FMN     Fire Dispatch
188. 154.19000  KED962  B   186.2 PL    BX/SI Disp  Bronx/Staten Island Dispatch    FM  Fire Dispatch
189. 154.37000  KEB525  B   186.2 PL    BK Disp Brooklyn Dispatch   FM  Fire Dispatch
190. 153.95000  KV2288  M       BK Mob  Brooklyn Mobiles    FM  Fire Dispatch
191. 154.25000  KEB523  B   186.2 PL    MN Disp Manhattan Dispatch  FM  Fire Dispatch
192. 154.01000  KV2288  M       MN Mob  Manhattan Mobiles   FM  Fire Dispatch
193. 154.40000  KEB526  B   186.2 PL    QN Disp Queens Dispatch     FM  Fire Dispatch
194. 154.43000  KEB524  B   186.2 PL    CW Disp Citywide Dispatch   FM  Fire Dispatch

## 8. Fireground, Interop

*offset: +210*

### Fireground

211. 486.11250  WPPU560     M   CSQ FG A/B/C 1  TAC 1   FM  Fire-Tac
212. 485.18750  WPPU560     M   CSQ FG A/B/C 2  CMD 1 - Command 1   FM  Fire-Tac
213. 486.26250  WPPU560     M   CSQ FG A/B/C 3  TAC 2   FM  Fire-Tac
214. 487.26250  WPPU560     M   CSQ FG A/B/C 4  HT4 - Fireground    FM  Fire-Tac
215. 487.13750  WPPU560     M   CSQ FG A5   HT5 - Fireground    FM  Fire-Tac
216. 485.26250  WPPU560     M   CSQ FG A6   HT6 - Fireground    FM  Fire-Tac
217. 486.13750  WPPU560     M   CSQ FG A7   HT7 - Fireground    FM  Fire-Tac
218. 485.06250  WPPU560     M   CSQ FG A8   HT8 - Fireground    FM  Fire-Tac
219. 486.01875  WPPU560     M       FG A9   HT9 - Fireground    P25     Fire-Tac
220. 483.01250  WPPU560     RM  173.8 PL    FG A11  High-Rise In-Building Repeater  FM  Fire-Tac
221. 484.76250  WPPU560     RM  173.8 PL    FG A12  Battalion Chief Vehicle Repeater    FM  Fire-Tac
222. 460.57500  KLO330  RM  127.3 PL    FG A14  Subway Repeater 1   FM  Fire-Tac
223. 460.62500  KLO330  RM  91.5 PL FG A15  Subway Repeater 2   FM  Fire-Tac
224. 486.73750  WPPU560     M   CSQ FG A/B/C 16 Emergency   FM  Fire-Tac
225. 156.65000  KIL820  BM  CSQ Fireboat Ops    Fireboat Operations     FM  Fire-Tac

### NYP/NYFD Interop

*offset: +225*

226. 482.73750  WIM475  RM  136.5 PL    IO Bronx    Bronx InterOp   FM  Interop
227. 482.78750  WIM471  RM  151.4 PL    IO Brooklyn Brooklyn InterOp    FM  Interop
228. 482.71250  WIM479  RM  123.0 PL    IO Manhattan    Manhattan InterOp   FM  Interop
229. 482.81250  WIM676  RM  167.9 PL    IO Queens   Queens InterOp  FM  Interop
230. 482.83750  WIM580  RM  186.2 PL    IO SI North Staten Island North InterOp     FM  Interop
231. 482.53750  WIM507  RM  186.2 PL    IO SI South Staten Island South InterOp     FM  Interop
232. 482.68750  WIM483  RM  110.9 PL    IO Citywide Citywide InterOp    FM  Interop
233. 482.38750  WIM515  RM  110.9 PL    IO CW SI    Citywide Staten Island InterOp  FM  Interop

## 9. EMS

*offset: +240*

241. 483.20625  WQFH239     RM  167.9 PL    Bronx N Dis Bronx North Dispatch    FMN     EMS Dispatch
242. 482.76875  WQFH239     RM  173.8 PL    Bronx S Dis Bronx South Dispatch    FMN     EMS Dispatch
243. 482.50625  WQFH239     RM  186.2 PL    Brklyn C Dis    Brooklyn Central Dispatch   FMN     EMS Dispatch
244. 483.28125  WQFH239     RM  173.8 PL    Brklyn N Dis    Brooklyn North Dispatch     FMN     EMS Dispatch
245. 483.29375  WQFH239     RM  192.8 PL    Brklyn S Dis    Brooklyn South Dispatch     FMN     EMS Dispatch
246. 482.98125  WQFH238     RM  156.7 PL    Manhat C Dis    Manhattan Central Dispatch  FMN     EMS Dispatch
247. 482.75625  WQFH238     RM  151.4 PL    Manhat N Dis    Manhattan North Dispatch    FMN     EMS Dispatch
248. 483.21875  WQFH238     RM  162.2 PL    Manhat S Dis    Manhattan South Dispatch    FMN     EMS Dispatch
249. 483.03125  WQFH239     RM  141.3 PL    Queens E Dis    Queens East Dispatch    FMN     EMS Dispatch
250. 482.51875  WQFH239     RM  146.2 PL    Queens W Dis    Queens West Dispatch    FMN     EMS Dispatch
251. 482.24375  WQFH239     RM  136.5 PL    SI Dis  Staten Island Dispatch  FMN     EMS Dispatch
252. 482.16875  WQFH238     RM  156.7 PL    Citywide1Dis    Citywide 1 Dispatch     FMN     EMS Dispatch
253. 482.21875  WQFH238     RM  162.2 PL    Citywide2Dis    Citywide 2 Dispatch     FMN     EMS Dispatch
254. 482.98125  WQFH239     M   167.9 PL    Bronx N Tac Bronx North Tactical    FMN     EMS-Tac
255. 483.21875  WQFH239     M   167.9 PL    Bronx S Tac Bronx South Tactical    FMN     EMS-Tac
256. 482.51875  WQFH239     M   167.9 PL    Brklyn C Tac    Brooklyn Central Tactical   FMN     EMS-Tac
257. 483.20625  WQFH239     M   167.9 PL    Brklyn N Tac    Brooklyn North Tactical     FMN     EMS-Tac
258. 482.76875  WQFH239     M   167.9 PL    Brklyn S Tac    Brooklyn South Tactical     FMN     EMS-Tac
259. 483.28125  WQFH239     M   167.9 PL    Manhat C Tac    Manhattan Central Tactical  FMN     EMS-Tac
260. 483.03125  WQFH239     M   167.9 PL    Manhat N Tac    Manhattan North Tactical    FMN     EMS-Tac
261. 483.29375  WQFH239     M   167.9 PL    Manhat S Tac    Manhattan South Tactical    FMN     EMS-Tac
262. 482.75625  WQFH239     M   167.9 PL    Queens E Tac    Queens East Tactical    FMN     EMS-Tac
263. 482.50625  WQFH239     M   167.9 PL    Queens W Tac    Queens West Tactical    FMN     EMS-Tac
264. 482.76875  WQFH239     M   167.9 PL    SI Tac  Staten Island Tactical  FMN     EMS-Tac
265. 482.50625  WQFH239     M   85.4 PL Tactical 1  Citywide Tactical 1     FMN     EMS-Tac
266. 487.48750  WQHX483     M   85.4 PL EMS CFR EMS CFR Tactical    FMN     EMS-Tac
267. 155.35500  WPLW539     RM  506 DPL CPMU Main   Central Park Medical Unit - Main    FM  EMS Dispatch

### Roosevelt Island Search and Rescue

*offset: +267*

268. 464.21250  WQKK660     RM  118.8 PL    RISAR   Search and Rescue Ch. 1     FM  EMS Dispatch
269. 464.21250  WQKK660     RM  74.4 PL RI PS 1 Disp    Public Safety Ch. 1 Dispatch    FM  Security
270. 464.15000  WQJV687     RM  167.9 PL    RI PS 2 Public Safety Ch. 2     FM  Security

## 10. Parks/Rec, Sanitation, Traffic

*offset: +270*

### Parks and Recreation

271. 151.29500  KGC210  RM  107.2 PL    Park Mnt/Ops    Maintenance and Operations (input tone varies by borough)   FM  Public Works
272. 151.20500  KNGZ785     RM  186.2 PL    PrkEnfPatSec    Parks Enforcement Patrol - Security     FM  Security
273. 155.26500      RM  186.2 PL    PrkEnfPat SI    Parks Enforcement Patrol - SI   FM  Security
274. 155.89500  KFF369  B   125 DPL PrkEnfPatBch    Parks Enforcement Patrol - Beach    FM  Security
275. 155.26500      RM  065 DPL PrkLifegrdRB    Lifeguards - Rockaway Beach     FM  EMS-Tac
275. 155.26500      RM  125 DPL PrkLifegrdCI    Lifeguards - Coney Island Beach     FM  EMS-Tac
275. 155.26500      RM  503 DPL PrkLifegrdOB    Lifeguards - Orchard Beach  FM  EMS-Tac
276. 151.26500      M   026 DPL Prk Pt-to-Pt    Point to Point  FM  Public Works

### Transit Authority

*offset: +276*

277. 156.10500  KRB407  M   67.0 PL Signals Signal Department   FM  Transportation
278. 160.84500      M       Yard    Yard    FM  Transportation
279. 161.19000  WNGX516     BM  127.3 PL    IRT Subway  IRT Subway  FM  Transportation
280. 161.50500  KTA927  BM  127.3 PL    BMT Subway  BMT Subway  FM  Transportation
281. 161.56500  KTA927  BM  127.3 PL    IND Subway  IND Subway  FM  Transportation
282. 470.38750  KGK700  RM      Power Sectn Power Section (various tones used)  FM  Transportation
283. 470.43750      RM  141.3 PL    SI Railway  Staten Island Railway   FM  Transportation
284. 470.48750  WPVS838     RM  123.0 PL    MOW Maintenance of Way  FM  Transportation

### Traffic

*offset: +284*

285. 471.16250  KWV660  R   151.4 PL    CITYWIDE    Intersection Ctrl/Tfc Intell/Nighthawks     FM  Law Dispatch
286. 472.61250  KWV660  R   151.4 PL    MANH/SI Manhattan/S.I. Summons Enforcement  FM  Law Dispatch
287. 453.25000  KWV660  R   151.4 PL    BRONX   Bronx Summons Enforcement   FM  Law Dispatch
288. 471.21250  KWV660  R   151.4 PL    BKLYN   Brooklyn Summons Enforcement    FM  Law Dispatch
289. 471.18750  KWV660  R   151.4 PL    QUEENS  Queens Summons Enforcement  FM  Law Dispatch
290. 453.82500  KSI296  RM  151.4 PL    Trfc Enfc 3A    Enforcement 3A  FM  Law Dispatch
291. 453.95000  KQP434  RM  151.4 PL    Trfc Enfc 3B    Enforcement 3B  FM  Law Dispatch
