All energies in the *rxn_energies.txt files are in kcal/mol.
The following numbering of the tested approaches is adopted in the *rxn_energies.txt files:

1	(T,Q)Z[FC/ T/ NormalPNO] + dE(CV,wCTZ) + dE(IT) + dE(PNO[CPS(6,7)])
2	(T,Q)Z[FC/ T/ NormalPNO] + dE(CV,wC(D,T)Z) + dE(IT) + dE(PNO[CPS(6,7)])
3	(T,Q)Z[FC/ T/ NormalPNO] + dE(CV,wCTZ) + dE(IT) + dE(PNO[TightPNO])
4	(T,Q)Z[FC/ T/ NormalPNO] + dE(CV,wC(D,T)Z) + dE(IT) + dE(PNO[TightPNO])
5	(T,Q)Z[FC/ T/ NormalPNO] + dE(CV,wCTZ) + dE(IT) + dE(PNO[CPS(5,6)])
6	(T,Q)Z[FC/ T/ NormalPNO] + dE(CV,wC(D,T)Z) + dE(IT) + dE(PNO[CPS(5,6)])
7	(T,Q)Z[FC/ T/ CPS(6,7)] + dE(CV,wCTZ) + dE(IT) 
8	(T,Q)Z[FC/ T/ CPS(6,7)] + dE(CV,wC(D,T)Z) + dE(IT)
9	(T,Q)Z[FC /T /TightPNO] + dE(CV,wCTZ) + dE(IT) 
10	(T,Q)Z[FC/ T/ TightPNO] + dE(CV,wC(D,T)Z) + dE(IT)
11	(T,Q)Z[FC/ T/ CPS(5,6)] + dE(CV,wCTZ) + dE(IT) 
12	(T,Q)Z[FC/ T/ CPS(5,6)] + dE(CV,wC(D,T)Z) + dE(IT)
13	(T,Q)Z[FC/ T1/ NormalPNO] + dE(CV,wCTZ) +dE(PNO[CPS(6,7)])
14	(T,Q)Z[FC/ T1/ NormalPNO] + dE(CV,wC(D,T)Z) +dE(PNO[CPS(6,7)])
15	(T,Q)Z[FC/ T1/ NormalPNO] + dE(CV,wCTZ) +dE(PNO[TightPNO])
16	(T,Q)Z[FC/ T1/ NormalPNO] + dE(CV,wC(D,T)Z) +dE(PNO[TightPNO])
17	(T,Q)Z[FC/ T1/ NormalPNO] + dE(CV,wCTZ) +dE(PNO[CPS(5,6)])
18	(T,Q)Z[FC/ T1/ NormalPNO] + dE(CV,wC(D,T)Z) +dE(PNO[CPS(5,6)])
19	(T,Q)Z[FC/ T1/ CPS(6,7)] + dE(CV,wCTZ) 
20	(T,Q)Z[FC/ T1/ CPS(6,7)] + dE(CV,wC(D,T)Z)
21	(T,Q)Z[FC /T1 /TightPNO] + dE(CV,wCTZ) 
22	(T,Q)Z[FC/ T1 / TightPNO] + dE(CV,wC(D,T)Z)
23	(T,Q)Z[FC/ T1/ CPS(5,6)] + dE(CV,wCTZ) 
24	(T,Q)Z[FC/ T1/ CPS(5,6)] + dE(CV,wC(D,T)Z)
25	(wCT,wCQ)Z[AE/ T/ NormalPNO] + dE(IT) + dE(PNO[CPS(6,7)])
26	(wCT,wCQ)Z[AE/ T/ NormalPNO] + dE(IT) + dE(PNO[TightPNO])
27	(wCT,wCQ)Z[AE/ T/ NormalPNO] + dE(IT) + dE(PNO[CPS(5,6)])
28	(wCT,wCQ)Z[AE/ T/ CPS(6,7)] + dE(IT)
29	(wCT,wCQ)Z[AE/ T/ TightPNO] + dE(IT)
30	(wCT,wCQ)Z[AE/ T/ CPS(5,6)] + dE(IT)
31	(wCT,wCQ)Z[AE/ T1/ NormalPNO] + dE(PNO[CPS(6,7)])
32	(wCT,wCQ)Z[AE/ T1/ NormalPNO] + dE(PNO[TightPNO])
33	(wCT,wCQ)Z[AE/ T1/ NormalPNO] + dE(PNO[CPS(5,6)])
34	(wCT,wCQ)Z[AE/ T1/ CPS(6,7)]
35	(wCT,wCQ)Z[AE/ T1/ TightPNO]
36	(wCT,wCQ)Z[AE/ T1/ CPS(5,6)] 
37	def2-(T,Q)Z[FC/ T/ NormalPNO] + dE(IT) + dE(PNO[CPS(6,7)])
38	def2-(T,Q)Z[FC/ T/ NormalPNO] + dE(IT) + dE(PNO[TightPNO])
39	def2-(T,Q)Z[FC/ T/ NormalPNO] + dE(IT) + dE(PNO[CPS(5,6)])
40	def2-(T,Q)Z[FC/ T/ CPS(6,7)] + dE(IT) 
41	def2-(T,Q)Z[FC/ T/ TightPNO] + dE(IT)
42	def2-(T,Q)Z[FC/ T/ CPS(5,6)] + dE(IT)
43	def2-(T,Q)Z[FC/ T1/ NormalPNO] + dE(PNO[CPS(6,7)])
44	def2-(T,Q)Z[FC/ T1/ NormalPNO] + dE(PNO[TightPNO])
45	def2-(T,Q)Z[FC/ T1/ NormalPNO] + dE(PNO[CPS(5,6)])
46	def2-(T,Q)Z[FC/ T1/ CPS(6,7)] 
47	def2-(T,Q)Z[FC/ T1/ TightPNO] 
48	def2-(T,Q)Z[FC/ T1/ CPS(5,6)] 
49	B3LYP-D3(BJ)
50	B3LYP-D4
51	PBE0-D3(BJ)
52	PBE0-D4
53	r2SCAN-D3(BJ)
54	r2SCAN-D4
55	M06-D3(0)
56	B2PLYP-D4
57	PWPB95-D4
58	wB97M-V
59	B97-3c
60	r2SCAN-3c
