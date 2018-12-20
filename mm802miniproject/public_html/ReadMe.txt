This is the readme file for this program.

Submitted file description:
"index.html" ------ main page of this project, displaying the outcome.

"d3.js" and "d3.min.js" ------ D3 librariy files we used in the project.

"mental health world - Sheet1.csv" ------ data file, including the data we used.

"mini-report.pdf" ------ project report written by Shang Lu

"presentation slide.pdf" ------ draft of the presentation slide for our project, any revision could be done before presentation.


How To:
1. To access the web page we built, users can either go to http://mm802ass3html.azurewebsites.net/,or set up a local server then load the web page through a browser. The web page is named "index.html" in the folder, with the dataset named "mental health world - Sheet1.csv" next to it.

2. On top of the web page, there are two select forms for choosing X and Y variables. Users can choose X variable between GDP growth rate and GDP per capita, choose Y variable among Prevalence of Depressive Disorder, Prevalence of Anxiety Disorder, Prevalence of Both Mental Disorder, Health Loss of Depressive Disorder,Health Loss of Anxiety Disorder and Health Loss of Both Mental Disorder.

3. After choosing X and Y variables, users have to click the "Create" button. Then the graph is generated. On the graph, each circle presents a country, with its X and Y position presenting values on X and Y variables, its color presenting region it belongs to, and its size presenting certain index. On top of the graph, the title shows the corresponding X and Y axes names. Under the title, an explanation tells the meaning of circle sizes. Under that, the mapping between circle colors and WHO regions is shown.

4. When users move their mouses onto a circle, the circle will becomes grey. Also a text box will pop out showing the country name and the index value of the circle size for corresponding circle. Two dashed lines appear as well, passing the circle and being perpendicular to each axis, assisting users in knowing the exact values on X and Y variables.

5. When X variable is chosen as GDP per capita, the X axis is transferred into Log function in order to display the data evenly.