# **Kpop Boy Groups and the Entertainment Companies Who Create Them** #

**Project Description**

![](https://user-images.githubusercontent.com/105595555/180062468-db33ce72-6609-4f5c-9a79-066538397ba1.png)
*Credit to allkpop.com for image*

The purpose of this project is to analyze the structure of Korean (aka kpop) boy groups along with other aspects of the industry related to the creation of boy groups. Unlike western boybands that seem to rotate in and out of the cultural zeitgeist, in kpop boy groups are a staple and multiple groups debut every year with various levels of success. With this project, I will analyze the common structure of a boy group including the number of original members and how common it is for groups to lose members, as well as when they debuted and what companies are debuting the most groups. To do this, I've obtained data from Kaggle [thanks to dbkpop](https://www.kaggle.com/code/mpwolke/kpop-idols-boy-groups/data?select=kpop_idols_boy_groups.csv).

I would like to take this time to explain a couple of terms related to kpop that I will use in this project.

* Big 3: The Big 3 is a group of Korean entertainment companies who are some of the oldest and most successful companies in the industry. They created the trainee structure as it is today and all three companies are known for their unique contributions to the industry. SM Entertainment, YG Entertainment, and JYP Entertainment are the Big 3 and they are known for vocal abilities, rap abilities, and dance, respectively. There are many entertainment companies in South Korea that debut groups every year, but these three groups have maintained a stronghold on the industry since the mid-1990s.
* Kpop generations: Korean media outlets will often refer to groups as belonging to different generations of kpop, e.g. first generation, second generation, etc. Any group debuting in 2022 is considered a fourth generation group. These categories don't often mean anything, they are more of a time marker for the industry and are sometimes associated with certain success markers. For example, people might give the second generation of kpop credit for contributing the Korean Wave of the late-2000s.

**Set-up**

* Clone my git repository and move into its directory: git clone https://github.com/alishacopley/KpopDataAnalysis.git

* To run this project, you will need to:
  * pip install pandas
  * pip install matplotlib
  * pip install numpy

* Run the Jupyter notebook: kpop-boy-groups-analysis.ipynb

**Features Used**

1. I read in data from a local .csv file using pd.read_csv.

2. I cleaned the data up by dropping categories that weren't necessary for my project, such as the name of the groups in all formats and the fandom names.   

3.  I analyzed my data by using five different calculations with pandas. I used min(), max(), median(), mode(), and sum() to analyze the members, original members, debut, and companies columns of data.

4. I used matplotlib to visualize the data into a pie chart and a bar graph. Specifically, I made a pie chart to how many groups are active vs. how many are inactive or on hiatus. I also made a bar graph to show how many groups the Big 3 companies have debuted over the years.

5. I used markdown cells to explain my thought process and the code in my project.
