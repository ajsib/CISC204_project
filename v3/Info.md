<h1>Info.txt - Commit Changes</h1>

e_nsi = ith card in hand is of value n and suit s
p_ns = piled card is value n and suit s
h_ni = e_nsi card is highest card in deck
w = when user sum less than eq to 7
m_qn = e_nsi has q duplicate cards with same value n
s_mqn = p_ns has q duplicates in hand
f_cs = e_nsi has c consecutive cards with same s
sf_cs = p_ns has c consecutive cards with same s in hand
smh_qn = no s_mqn higher in q
sfh_cs = sf_cs is true && no other sf_cs is higher in c
mh_qn = m_qn is true && no other m_qn is higher in q value
c = true when possible conflict between two possible moves, one removing a potential group for next round
gs_r = the sum of the group that contains pot card (s group) is greater than the sum group in hand.
hs_r = evaluating the a highest group within hand + pile
hR_r = highest group in only h group.
pd_h = placing group with highest sum into pot
us = option 1
ud = option 2
l = pile card less than 7

__Constraints__ 

smh_qn \to sm_qn
mh_qn \to m_qn