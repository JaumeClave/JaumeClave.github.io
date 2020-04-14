<!-- Website -->
<p><a href="https://www.linkedin.com/in/jaume-clave-domenech/" target="_blank">
<img alt="GitHub" src="https://jaumeclave.github.io./images/linkedin_logo.png" height="17"></a>
<a href="https://github.com/JaumeClave" target="_blank">
<img alt="GitHub" src="https://jaumeclave.github.io./images/github_logo.png" height="18" hspace="20"></a>
<a href="mailto:j.clavedomenech@gmail.com" target="_blank">
<img alt="Gmail" src="https://jaumeclave.github.io./images/gmail_logo.png" height="18"></a></p>

<img src="https://jaumeclave.github.io./images/jaume_clave.jpg" width="200" align="right"/>

# Data science portfolio by Jaume Clave Domenech
<p align="justify">This portfolio is a compilation of notebooks which I created for data analysis and for exploration of machine learning algorithms. It contains work from my time completing my MSc Business Analytics at Imperial College Business School, my professional career and various projects I have completed out of interest and curiosity.</p>

## Projects
<h3 id="networkx-community-detection">Community Detection using NetworkX</h3>
<p><a href="https://github.com/JaumeClave/community_detection_NetworkX/blob/master/community_detection-networkx.ipynb" target="_blank">Github</a> 
<a href="https://nbviewer.jupyter.org/github/JaumeClave/community_detection_NetworkX/blob/master/community_detection-networkx.ipynb" target="_blank">nbviewer</a></p>

<img src="https://jaumeclave.github.io./images/louvian_wttw.JPG" width="350" align="right"/>

<p align="justify">Networks are graphs which are made out of nodes and edges and they are present everywhere. Social networks of usesrs owned by the likes of Favebook and Twitter contain sensitive relationship data, biological networks help analyse patterns in biological systems, such as food-webs and predator-prey interactions and narrative networks help identify key actors and the key communities or parties they are involved with. The study of a network is essential in order to learn about its information spread, players of influence and its robustness. Networks inherently contain communities, areas of densely connected nodes which provide information about the network, among that information, it allows for the creation of large scale maps of a network since individual communities act like meta-nodes in the network. NetworkX is a Python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks. <b>This project</b> utilises NetwokX to investigate two different netowrks, studying key centrality measures and utilising the Girvan–Newman and the Louvain Modularity methods to explore network communities.</p>

<h3 id="networkx-asset-price-correlations">Visualising Asset Price Correlations</h3>
<p><a href="https://github.com/JaumeClave/asset_price_correlation_NetworkX/blob/master/asset_price_correlation.ipynb" target="_blank">Github</a> 
<a href="https://nbviewer.jupyter.org/github/JaumeClave/asset_price_correlation_NetworkX/blob/master/asset_price_correlation.ipynb" target="_blank">nbviewer</a></p>

<img src="https://jaumeclave.github.io./images/clustured_heatmap.JPG" width="350" align="right"/>

<p align="justify">“Diversify your portfolio!” Words everyone has heard and a portfolio managers priority. Diversifying methods vary from selecting different asset classes (funds, bonds, stocks, etc.), combining industries, or varying the risk levels of investments. And the most common and direct diversification measurement used in these methods is correlation. Correlation is how closely variables are related and it may be measured with Pearsons correlation coefficient, the degree of linear relationship between two variables. Its values range between -1 (perfect negative correlation) and 1 (perfect positive correlation). While a zero correlation implies no relationship between variables. True diversification is therefore only realistically achieved by investing in assets which are uncorrelated (0) with each other. <b>This project</b> uses NetworkX and nxviz to investigate and visualize these relationships and investigate price correlations for 39 different assets (currencies, commodities, equities and bonds) with the aim of showing an investor what assets they might need to hold to truly diversify their portfolio.</p>

<h3 id="data-analysis-and-machine-learning-airbnb-new-orleans">Exploring & Machine Learning with Airbnb Listings in New Orleans</h3>
<p><a href="https://github.com/JaumeClave/inside_airbnb_new_orleans_analysis/blob/master/inside_airbnb_new_orleans_analysis.ipynb" target="_blank">Github</a> 
<a href="https://nbviewer.jupyter.org/github/JaumeClave/inside_airbnb_new_orleans_analysis/blob/master/inside_airbnb_new_orleans_analysis.ipynb" target="_blank">nbviewer</a></p>

<img src="https://jaumeclave.github.io./images/new_orleans_neigborhoods_sentiment.JPG" width="350" align="right"/>  

<p align="justify"><b>This project</b> provides an analysis and evaluation of the current and prospective Airbnb listings in New Orleans (NO), Louisiana. The report intends to contribute information and advice to potential visitors. Methods of analysis include sentiment analysis, data and feature aggregation as well as visualizations such as boxplots, spatial mappings and calendar plots. Other calculations include occupancy rate, prices and trip length averages. Results show that occupancy rate is higher during key dates in NO. In particular, during NOs large events such as the BUKU Music and Art Project and the New Orleans Jazz and Heritage Festival. This produces an increment in property price and demand. The report finds that the prospects of Airbnb in the NO community is positive because of high (+80) review scores across all neighborhoods and property types. The majority of properties are of type “house” with a categorized size of small and medium, ideal for families and groups of friends. Properties in summer months are comparatively available resulting in a peaceful and quite vacation.</p>

<h3 id="forecasting-lettuce-demand-in-fast-food-resturants">Forecasting Ingredient Demand for Fast Food Resturants in New York and California</h3>
<p><a href="https://github.com/JaumeClave/lettuce_forecast/blob/master/README.md" target="_blank">Github</a></p>

<img src="https://jaumeclave.github.io./images/unnamed-chunk-54-1.png" width="350" align="right"/>  

<p align="justify">Forecasting is present in all industries. The ability to make predictions of the future based on past and present data and most commonly by analysis of trends is key to success in any market because if done successfully it may drastically reduce costs and increase company revenue and profit. The food industry in this sense, is no different. With ever-changing tastes, tight profit margins, and fickle consumers, the need for accurate projections is an essential component of business success. Industry leaders use state of the art forecasting techniques, centralized data sources and machine learning algorithms to get a step ahead of the competition and to optimaly manage their supply chain. In general however, the problem the industry faces lies with scattered data sources, insufficient consideration of external factors, such as campaigns and promotions, moving holidays, weather and ad hoc solutions. <b>This project</b> forecasts the daily demand for ingredients in a fast-food chain in two different major US markets; New York and Califronia. Each resturants historic data is examined and the data is checked for stationarity, tansformed and forecasted through an ETS model and a Holt-Winters model. An ARIMA model is also used to forecsat in order to test various methods. Finally all three models are evaluated against eachother using various estimators of prediction errors and the best is chosen for each individual resturant location.</p>
