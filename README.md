<h1>NYC-Taxi EDA Detailed Analysis</h1>


<h2>Description</h2>
I conducted a detailed analysis of a dataset containing New York City taxi trip durations. After importing the dataset, I examined the first few rows to familiarize myself with the data structure. To gain insights into the dataset, I calculated various descriptive statistics such as the mean, standard deviation, minimum, maximum, and quartiles for columns like vendor ID, passenger count, and trip duration.

To visualize the data, I created several plots using libraries like Matplotlib and Seaborn. I plotted a bar graph to display the frequency distribution of the "store_and_fwd_flag" variable, which indicated whether the trip data was stored in the vehicle before forwarding. I also generated a count plot to visualize the distribution of vendor IDs in the dataset.

To explore the spatial aspects of the data, I plotted a scatter plot to visualize the pickup locations using longitude and latitude coordinates. This allowed me to identify any visible patterns or clusters in the data.

To analyze the relationship between passenger count and trip duration, I used a box plot. The plot revealed any potential outliers and provided insights into how trip duration varied with passenger count.

Next, I delved into the temporal aspects of the data by extracting the hour of the day from the "pickup_datetime" column. Using box plots, I examined how trip duration varied across different hours of the day. I also created separate plots excluding outliers to focus on the central tendencies of trip durations.

To investigate whether there were significant differences in trip durations between different vendor IDs, I performed a t-test. By comparing the trip durations of vendors 1 and 2, I calculated the t-value and p-value to assess the statistical significance of the observed differences.

Overall, this comprehensive analysis allowed me to gain a deeper understanding of the New York City taxi trip duration dataset. I explored the data from various angles, including spatial, temporal, and categorical perspectives, and generated visualizations and statistical tests to uncover patterns, relationships, and insights within the data.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Libraries: Pandas, NumPy, Matplotlib, Seaborn</b>

<h2>Environments Used </h2>

- <b>Juputer Notebook</b>

