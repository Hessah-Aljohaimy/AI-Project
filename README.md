# AI Project for SWE 485 | G3 | Water Quality

Student Name : Khawlah Alnayel | Student ID : 441200943

Student Name : Sarah Alomar | Student ID : 441200917

Student Name : Hessah Aljohaimy | Student ID : 441201152

---

# Introducation

Every human being needs clean water for intake. The World Health Organization (WHO) estimates that 80% of illnesses are water-borne. Industrialization, discharge of internal waste, radioactive waste, population growth, unnecessary use of pesticides, fertilizers and leakage from water tanks are key sources of water effluence. In Addition, there are negative health effects associated with these wastes. Different chemicals have dissimilar affects depending on their positions and categories. Bacterial, viral and parasitic diseases like typhoid, cholera, encephalitis, poliomyelitis, hepatitis, skin infection and gastrointestinal disease are spreading through polluted water [1].

Therefore, it is recommended to examine the water quality on a regular basis to avoid its destructive effects on human health. As a matter of fact, the availability of safe drinking water is one of the most vital components of effective health protection policy and constitutes a fundamental human right. This is important as a health and development issue at a national, regional and local level. In some regions, it has been shown that investments in water supply and sanitation can yield a net economic benefit, since the reductions in adverse health effects and health care costs outweigh the costs of undertaking the interventions [2].

Our aim to predict the quality of water from 3272 different water bodies where we have the pH value ,Hardness , Solids , Chloramines , Sulfate , Conductivity , Organic carbon , Trihalomethanes , Turbidity all in different values then we have the probability to indicate whether the water is safe or not and to understand the relationship between these different values and the quality of water.

[1]mportance of safe drinking water for human life - researchgate (no date). Available at: https://www.researchgate.net/publication/341539508_Importance_of_Safe_Drinking_Water_for_Human_Life (Accessed: April 23, 2023).

[2]Kadiwal, A. (2021) Water quality, Kaggle. Available at: https://www.kaggle.com/datasets/adityakadiwal/water-potability (Accessed: April 23, 2023).

---

# About Dataset:

Context

Access to safe drinking-water is essential to health, a basic human right and a component of effective policy for health protection. This is important as a health and development issue at a national, regional and local level. In some regions, it has been shown that investments in water supply and sanitation can yield a net economic benefit, since the reductions in adverse health effects and health care costs outweigh the costs of undertaking the interventions.

Content

The water_potability.csv file contains water quality metrics for 3276 different water bodies.

1. pH value:
   PH is an important parameter in evaluating the acid–base balance of water. It is also the indicator of acidic or alkaline condition of water status. WHO has recommended maximum permissible limit of pH from 6.5 to 8.5. The current investigation ranges were 6.52–6.83 which are in the range of WHO standards.

2. Hardness:
   Hardness is mainly caused by calcium and magnesium salts. These salts are dissolved from geologic deposits through which water travels. The length of time water is in contact with hardness producing material helps determine how much hardness there is in raw water. Hardness was originally defined as the capacity of water to precipitate soap caused by Calcium and Magnesium.

3. Solids (Total dissolved solids - TDS):
   Water has the ability to dissolve a wide range of inorganic and some organic minerals or salts such as potassium, calcium, sodium, bicarbonates, chlorides, magnesium, sulfates etc. These minerals produced un-wanted taste and diluted color in appearance of water. This is the important parameter for the use of water. The water with high TDS value indicates that water is highly mineralized. Desirable limit for TDS is 500 mg/l and maximum limit is 1000 mg/l which prescribed for drinking purpose.

4. Chloramines:
   Chlorine and chloramine are the major disinfectants used in public water systems. Chloramines are most commonly formed when ammonia is added to chlorine to treat drinking water. Chlorine levels up to 4 milligrams per liter (mg/L or 4 parts per million (ppm)) are considered safe in drinking water.

5. Sulfate:
   Sulfates are naturally occurring substances that are found in minerals, soil, and rocks. They are present in ambient air, groundwater, plants, and food. The principal commercial use of sulfate is in the chemical industry. Sulfate concentration in seawater is about 2,700 milligrams per liter (mg/L). It ranges from 3 to 30 mg/L in most freshwater supplies, although much higher concentrations (1000 mg/L) are found in some geographic locations.

6. Conductivity:
   Pure water is not a good conductor of electric current rather’s a good insulator. Increase in ions concentration enhances the electrical conductivity of water. Generally, the amount of dissolved solids in water determines the electrical conductivity. Electrical conductivity (EC) actually measures the ionic process of a solution that enables it to transmit current. According to WHO standards, EC value should not exceeded 400 μS/cm.

7. Organic_carbon:
   Total Organic Carbon (TOC) in source waters comes from decaying natural organic matter (NOM) as well as synthetic sources. TOC is a measure of the total amount of carbon in organic compounds in pure water. According to US EPA < 2 mg/L as TOC in treated / drinking water, and < 4 mg/Lit in source water which is use for treatment.

8. Trihalomethanes:
   THMs are chemicals which may be found in water treated with chlorine. The concentration of THMs in drinking water varies according to the level of organic material in the water, the amount of chlorine required to treat the water, and the temperature of the water that is being treated. THM levels up to 80 ppm is considered safe in drinking water.

9. Turbidity:
   The turbidity of water depends on the quantity of solid matter present in the suspended state. It is a measure of light emitting properties of water and the test is used to indicate the quality of waste discharge with respect to colloidal matter. The mean turbidity value obtained for Wondo Genet Campus (0.98 NTU) is lower than the WHO recommended value of 5.00 NTU.

10. Potability:
    Our dataset classified based on Potability which indicates if water is safe for human consumption where 1 means Potable and 0 means Not potable.
