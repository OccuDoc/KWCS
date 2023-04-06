# KWCS
5차 근로환경 조사와 6차 근로환경 조사를 merge하여
Low educational attainment와 Poor mental health 사이의 연관성을 Multidimensional precarious employment가 어떻게 중재하는지

Design: Cross-sectional Mediation analysis

Independent variable (IV) = Low educaitonal attainment (대졸, 고졸, 중졸, 초졸 이하로 분류)

Mediating variable (MV) = EPRES-E scale (developed by Padrosa Et. Al.) 
see: Padrosa, E., Belvis, F., Benach, J. et al. Measuring precarious employment in the European Working Conditions Survey: 
psychometric properties and construct validity in Spain. Qual Quant 55, 543–562 (2021). https://doi.org/10.1007/s11135-020-01017-2

Dependent variable (DV) = WHO well-being scale cut-off: 50점 이하

*Statistical analysis
R에서 logistic mediation은 불가하고, 데이터를 저장한 다음 Stata 에서 불러내어 ldecomp 구문을 사용하여 분석

