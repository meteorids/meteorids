- 👋 Hi, I’m @meteorids
- :sunrise: I’m interested in Radiative Transfer.
- :telescope: I’m currently working on a radiation scheme for forecasting.
- :earth_americas: I’m looking to collaborate on radiative transfer. 
- :globe_with_meridians: Check out my website: [https://meteorids.github.io](https://meteorids.github.io)

### My main profile is:
 > ####  Radiative Transfer, Aerosols, Ozone, Instrumentation.


<!--- my enbeded card
more here: https://github.com/anuraghazra/github-readme-stats 
--->


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=meteorids&layout=compact&theme=gruvbox)](https://github.com/anuraghazra/github-readme-stats)

import matplotlib.pyplot as plt

# Custom language distribution
languages = ['Fortran', 'Python', 'Shell', 'Jupyter Notebook']
percentages = [40, 30, 20, 10]
colors = ['#f37726', '#3572A5', '#89e051', '#DA5B0B']

# Plot
fig, ax = plt.subplots()
ax.pie(percentages, labels=languages, colors=colors, startangle=90, counterclock=False, autopct='%1.0f%%')
ax.set_title('Custom Language Usage')
plt.axis('equal')
plt.tight_layout()
plt.savefig("custom_lang_pie.png", dpi=300)
plt.show()



<!---
meteorids/meteorids is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
