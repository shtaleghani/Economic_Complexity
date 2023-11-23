# economic-complexity
our perpose is to examine the effects of various factors on export growth, These factors are i) the maximum proximity of the product, which countries export with high Relative Comparative Advantage (RCA), ii) the ratio of exports of that product in the neighboring countries, and iii) the product complexity. here we calculate the variables and finally we estimate the model with Eviews.
# Maximum proximity
The proximity between products i and j is defined as the minimum of the pairwise conditional probabilities of a country exporting product i and product j at the same time.
![PROX](https://github.com/shtaleghani/economic-complexity/assets/126946750/81ccfdd6-f2e8-4d6f-a015-4aa029b425f4)

φ_ij=min(Prob(RCAx_i>1│RCAx_j>1),Prob(RCAx_j>1│RCAx_i>1))
RCA is Revealed Compared Advantage and defined as:
![RCA](https://github.com/shtaleghani/economic-complexity/assets/126946750/1eaa7e5d-f42f-4631-bea5-b3cedc0ded00)

 RCA_cp=((X_cp/(∑_c▒X_cp )))/(((∑_p▒X_cp )/(∑_c▒∑_p▒X_cp )) )
Where Xcp is the export value of product p in country c.
Maximum proximity is computed as follows: 
![MAXPROX](https://github.com/shtaleghani/economic-complexity/assets/126946750/7408c6bb-3598-43e0-a33b-c707b2f253e8)

Φ_CP (t)=MAX(φ_pi (t)) ∀ i ∈Π(c)
where Π(c) is the set of products with RCA>1 for country c.
# NBRCA
NBRCA  is calculated as follows:
![NBRCA](https://github.com/shtaleghani/economic-complexity/assets/126946750/f2ff4628-0986-4193-adeb-f4755b344eaa)

〖NBRCA〗_pc=(∑_(C^')▒〖BRCA〗_pc )/n_(c^' ) 
〖BRCA〗_pc={█(1,〖RCA〗_pc≥1@0,〖RCA〗_pc<1)┤
Where n_(c^' ) is the number of neighbors that country has. For example, if a country has five neighbors and three of them export product p with RCA>1 then the NBRCA will be 3\/5.

