# DeepSolar Bangladesh: A Novel Convolutional Neural Network (CNN) Architecture for the Detection of Solar Panels from Low Resolution Satellite Imagery in Developing Countries

See INSTRUCTIONS.md

**Authors:** Farihah Ahmed  (Columbia University), Barbara Duckworth (MIT)

**Mentor:** Barbara Duckworth

**QUICK INTRO:**  Due to its environmental benefits and decreasing costs, the supply of solar energy is growing at an accelerating pace globally. However, the decentralised nature of solar makes it difficult to keep track of the different photovoltaic (PV) systems deployed across a country. There is a critical need for highly accurate, comprehensive national databases of solar systems, which would allow policymakers, researchers, and the government to study socioeconomic trends in solar deployment. Manual surveys have shown to be inaccurate. The 2018 DeepSolar study by Yang et. al developed a deep-learning framework and national solar deployment database for the US using high-quality satellite imagery, which proved to be a much more efficient and accurate approach. However,
satellite imagery in developing countries such as Bangladesh is of much lower resolution and quality, and performed poorly with the original DeepSolar model by Yang et. al. 

**OUR SOLUTION:** Our study highlights the implementation of a novel convolutional neural network (CNN) in detecting solar panels through low resolution Google Static Maps API satellite imagery data. 

**APPROACH:** The model was trained over 500 epochs and had 49,859,906 parameters, and classified image samples as positive (indicating presence of solar panels) or negative (absence of solar panels).

**RESULTS:** Our accuracy was 86.49%, F1 score was 86.49%, precision was 91.95%, and recall score was 81.63%, which are comparable scores to the original DeepSolar CNN that was trained on much higher quality
data. 

**PROJECT IMPLICATIONS:** This was the first CNN to detect solar panels using low- resolution satellite imagery (which is usually the only option for developing countries), and showed to be highly accurate
and computationally efficient. Future plans include gathering funding to be able to purchase Google API satellite imagery to be able to cover all of Bangladesh to create a comprehensive public national database, as well as expanding to other developing countries.


Columbia Junior Science Journal submitted. For more details, see our paper.
