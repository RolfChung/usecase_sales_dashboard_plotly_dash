
# Summary: 
## usecase sales dashboard with Jupyter Dash


<p>
<b>Notice:</b><br>
A live version is deposited on Binder.<br>
"Binder allows you to create custom computing environments that can be shared and used by many remote users."<br>
This allows to see the Dash apps create in the notebooks locally in your browser.<br>
Jumpt directly to Binder for running the code of the repository:<br>
<a href="https://mybinder.org/v2/gh/RolfChung/usecase_sales_dashboard_plotly_dash/HEAD" target="_blank">usecase_sales_dashboard</a> 

</p>
<b>Notice 2:</b><br>
Unfortunately it turns out:<br>
Jupyterlab-dash needs to be included in built on Binder.<br>
Otherwise it produces an error and JupyterDash does not work in Binder like here. :-(.<br>
Hopefully there will be solution in the future to this problem by the developers.<br>
More on this on the <a href='https://discourse.jupyter.org/t/jupyterlab-dash-needs-to-be-included-in-built-on-binder/14164', target='blank'> Jupyter com forum</a>.


</p>



<p>
Dash made a great job bringing Dash to Jupyter.<br>
Normally you would develop and start Dash from an IDE and the command line.<br>
As this project is a demonstration of Dash capabilities JupyterDash was chosen.<br>
The JupyterDash has different modes of presentation: inline, jupyter lab, external.<br>
The repository here uses the inline and external modes.<br>
In external mode a link is created at the end of the notebook. This outputs the Dash app into a website.<br>
However Github does not allow to start Dash apps from notebooks right now.<br>
That is a reason a Binder version of this repository was created.<br>
One last word: <b>Dash needs Javascript to be installed on the machine to work.</b>
</p>


<p>
In general this repository builds a use case for Plotly Dash.<br>
It creates a sales dashboard for world wide e-commerce data.<br>
According to Wordnik a dashboard is <br>
"a user interface on a computer display that presents constantly updated information, such as processing speed, in a format that resembles the dashboard of a vehicle."<br>
This sales dashboard is intuitively understandable.    
<p>

<p>
On a technical level this project applies Plotly and JupyterDash for data visualization and web deployment.<br>
It is also applying HTML and CSS to structure and style the dashboard.
</p>

<p>
This notebook is part of larger project consisting of a portfolio of notebooks testing out different versions of the sales dashboard.<br>
There is also a dedicated notebook for importing and cleaning the data.<br>
The cleaned data can immediately used in the JupyterDash notebooks.<br>
It is followed up by another project adding interactivity to the sales dashboard.<br>
Then users can get particular information by sliding or klicking on graphic elements.<br>
</p>

