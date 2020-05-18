<!-- Website -->
<p><a href="https://www.linkedin.com/in/jaume-clave-domenech/" target="_blank">
<img alt="GitHub" src="https://jaumeclave.github.io./images/linkedin_logo.png" height="17"></a>
<a href="https://github.com/JaumeClave" target="_blank">
<img alt="GitHub" src="https://jaumeclave.github.io./images/github_logo.png" height="18" hspace="20"></a>
<a href="mailto:j.clavedomenech@gmail.com" target="_blank">
<img alt="Gmail" src="https://jaumeclave.github.io./images/gmail_logo.png" height="18"></a></p>

<img src="https://jaumeclave.github.io./images/jaume_clave.jpg" width="200" align="right"/>

# Data Science Portfolio by Jaume Clave Domenech
<p align="justify">This portfolio is a compilation of notebooks which I created for data analysis and for exploration of machine learning algorithms. It contains work from my time completing my MSc Business Analytics at Imperial College Business School, my professional career and various projects I have completed out of interest and curiosity.</p>

## Projects


<h3 id="networkx-community-detection">WhatsApp Group Chat AnalysisWwith Naive Bayes Message Categorization</h3>
<p><a href="https://github.com/JaumeClave/whatsapp_group_chat_analysis/blob/master/whatsapp_expansion_crew_final.ipynb" target="_blank">Github</a> 
<a href="https://nbviewer.jupyter.org/github/JaumeClave/whatsapp_group_chat_analysis/blob/master/whatsapp_expansion_crew_final.ipynb" target="_blank">nbviewer</a></p>

<a href="https://nbviewer.jupyter.org/github/JaumeClave/whatsapp_group_chat_analysis/blob/master/whatsapp_expansion_crew_final.ipynb" target="_blank">
<img src="https://jaumeclave.github.io./images/chat_polarity_scores.JPG" width="350" align="right"/></a>

<p align="justify">Facebook's purchase of the messaging giant for $16 billion ($4 billion cash, $12 billion in Facebook shares) back in 2014, further solidified Facebooks reach into user's everyday lives. The acquisition was one of the largest Silicon Valley had ever seen, and by far Facebook's largest purchase. So why did Facebook purchase an app that had limited revenue generation...? Growth potential and data. WhatsApp was the only app with higher engagement than Facebook itself. <a href="https://nbviewer.jupyter.org/github/JaumeClave/whatsapp_group_chat_analysis/blob/master/whatsapp_expansion_crew_final.ipynb" target="_blank"><b>This project</b></a> uses Python to explore the dataset and compute interesting top-level metrics. The paper aims to inform the reader about exploratory data analysis (EDA) methods and what they can show in relation to this type of data. The paper contains a detailed section on forecasting models including STL decomposition and ARIMA techniques that are utilised to forecast future message counts. The project studies an introduction into machine learning through natural language processing and the use of a Naive Bayes classifier for message segmentation. The visualizations go hand in hand with the explanations so as to provide a visual medium for the information.</p>


<h3 id="geometric-brownian-motion-black-sholes-delta-hedging">Geometric Brownian Motion and Black-Scholes Delta Hedging</h3>
<p><a href="https://github.com/JaumeClave/Geometric-Brownian-Motion-and-Black-Scholes-Delta-Hedging/blob/master/geometric_brownian_motion_and_black_scholes_delta_hedging.ipynb" target="_blank">Github</a> 
<a href="https://nbviewer.jupyter.org/github/JaumeClave/Geometric-Brownian-Motion-and-Black-Scholes-Delta-Hedging/blob/master/geometric_brownian_motion_and_black_scholes_delta_hedging.ipynb" target="_blank">nbviewer</a></p>

<a href="https://nbviewer.jupyter.org/github/JaumeClave/Geometric-Brownian-Motion-and-Black-Scholes-Delta-Hedging/blob/master/geometric_brownian_motion_and_black_scholes_delta_hedging.ipynb" target="_blank">
<img src="https://jaumeclave.github.io./images/monte_carlos.JPG" width="350" align="right"/></a>

<p align="justify">Summary statistics released in early January of 2020 by FIA show that trading activity in the global exchange-traded derivatives markets rose by 13.7% in 2019 to reach a record of 34.47 billion contracts. The options volume alone rose 16% to 15.23 billion contracts. Price movements in the options market are a reflection of decisions to buy or sell options made by millions of traders. Successful traders study the options daily trading volume and open interest when on the exchange. <a href="https://nbviewer.jupyter.org/github/JaumeClave/Geometric-Brownian-Motion-and-Black-Scholes-Delta-Hedging/blob/master/geometric_brownian_motion_and_black_scholes_delta_hedging.ipynb" target="_blank"><b>This project</b></a> introduces the options derivative and provides terminology and the mathematical notation behind essential option pricing models. A function is built to calibrate the binomial model so that its dynamics match that of GBM allowing for convergence of binomial model option prices to Black-Scholes prices. A Monte Carlo simulation of 10,000 paths is built to estimate the price of an Asian call option. The project assumes certain market conditions so that it becomes possible to dynamically replicate the payoff of a call option using a self-financing trading strategy. The strategy requires continuous and dynamic delta hedging in the Black-Sholes model which is investigated in order to create profit and loss computations based on option volatility.</p>


<h3 id="face-recognition-pca">Building a Facial Recognition Algorithm Using Principal Component Analysis (PCA)</h3>
<p><a href="https://github.com/JaumeClave/facial_recognition_with_pca/blob/master/face_detection_with_principal_component_analysis.ipynb" target="_blank">Github</a> 
<a href="https://nbviewer.jupyter.org/github/JaumeClave/facial_recognition_with_pca/blob/master/face_detection_with_principal_component_analysis.ipynb" target="_blank">nbviewer</a></p>

<a href="https://nbviewer.jupyter.org/github/JaumeClave/facial_recognition_with_pca/blob/master/face_detection_with_principal_component_analysis.ipynb" target="_blank">
<img src="https://jaumeclave.github.io./images/3d_pca.JPG" width="350" align="right"/>
</a>

<p align="justify">Facial recognition is utilized by SnapChat and Instagram to attract a wider user base amidst stiff competition from different applications through filters and animated lenses. Apple and Samsung have patented biometric authentication that utilize facial recognition sensors on the devices front. Facebook has a DeepFace system that employs a nine-layer neural network with over 120 million connection weights, trained on four million images uploaded by Facebook users. DeepFace shows human-level performance even outperforming us in various situations. This technology is outperforms the FBI's Next Generation Identification system. Competing with this is China which is developing facial recognition technology to identify people wearing surgical or dust masks by matching solely to eyes and foreheads. <a href="https://nbviewer.jupyter.org/github/JaumeClave/facial_recognition_with_pca/blob/master/face_detection_with_principal_component_analysis.ipynb" target="_blank"><b>This project</b></a> introduces principal component analysis to build a simple facial recognition model on two unique datasets. The unsupervised machine learning model is explained, visualized and mathematically expressed in order to build intuition. The eigenfaces are plotted from the original 4 faces along with k-dimensional reconstructions of them for k= 3, 10, 25, 50 and 200. Various machine learning models, L/QDA, Support Vector Classifier, Gaussian NB and a Multi-Layer Perceptron are built, tuned and fitted to the faces dataset for classification. Finally a synthetic dataset is created and a K-means clustering model is built. Performance of the model, the quality of the clusters, is compared to when the model is trained on raw data and to when it is trained on principal component vectors.</p>


<h3 id="logistic-regression-patient-readmittance">Using Logistic Regression to Predict Hospital Patient Readmittance</h3>
<p><a href="https://github.com/JaumeClave/tahoe_healthcare_readmittance_prediction/blob/master/tahoe_healthcare_systems.ipynb" target="_blank">Github</a> 
<a href="https://nbviewer.jupyter.org/github/JaumeClave/tahoe_healthcare_readmittance_prediction/blob/master/tahoe_healthcare_systems.ipynb" target="_blank">nbviewer</a></p>

<a href="https://nbviewer.jupyter.org/github/JaumeClave/tahoe_healthcare_readmittance_prediction/blob/master/tahoe_healthcare_systems.ipynb" target="_blank">
<img src="https://jaumeclave.github.io./images/roc_curve.JPG" width="350" align="right"/>  </a>

<p align="justify">The high readmission level of hospital patients after they are discharged from the hospital is a significant concern for the US health care system. It is estimated that 20% of all hospitalized Medicare patients are readmitted within 30 days of hospitalization and 34% are readmitted within 90 days. The estimated cost of hospital readmissions is about $17.4 billion annually. To address the problem, the 2010 Affordable Care Act established a hospital readmissions reduction program (HRRP). The program created financial incentives for hospitals to reduce readmissions by linking Medicare reimbursements to a hospital’s risk-adjusted readmission rate. For 2012, penalties could be as much 1% of the total reimbursements a hospital received for the three target conditions. In the first year of the program, 2,225 hospitals were subject to reduced payment penalties, with penalties totaling $225 million nationwide. The maximum penalties were set to increase to 3% of reimbursements by 2014.<a href="https://nbviewer.jupyter.org/github/JaumeClave/tahoe_healthcare_readmittance_prediction/blob/master/tahoe_healthcare_systems.ipynb" target="_blank"><b> This project </b></a> studies the hospitals readmission rate and the costs associated with the Medicare penalties. The paper also considers a CareTracker program that aims to help paitents post care and reduce readmission rates in order to reduce Medicare penalties. A logistic regression model is applied to determine the best possible threshold, based on patient readmittence probabiloty, to apply when deciding to offer the CareTracker program or not.</p>


<h3 id="networkx-asset-price-correlations">Risk Management Scenario Analysis and Markowitz Efficient Frontier Portfolio Optimisation</h3>
<p><a href="https://github.com/JaumeClave/scenario_analysis_and_modern_portfolio_theory_mpt_with_efficient_frontiers/blob/master/scenario_analysis_and_modern_portfolio_theory_with_efficient_frontiers.ipynb" target="_blank">Github</a> 
<a href="https://nbviewer.jupyter.org/github/JaumeClave/scenario_analysis_and_modern_portfolio_theory_mpt_with_efficient_frontiers/blob/master/scenario_analysis_and_modern_portfolio_theory_with_efficient_frontiers.ipynb" target="_blank">nbviewer</a></p>

<a href="https://nbviewer.jupyter.org/github/JaumeClave/scenario_analysis_and_modern_portfolio_theory_mpt_with_efficient_frontiers/blob/master/scenario_analysis_and_modern_portfolio_theory_with_efficient_frontiers.ipynb" target="_blank">
<img src="https://jaumeclave.github.io./images/efficient_frontiers.JPG" width="350" align="right"/>
</a>

<p align="justify">The use of scenarios in strategic decision making was pioneered by the Royal Dutch/Shell Company during the 1970s. The method is best suited to organizations and industries which are extremely sensitive to external factors beyond their control and where time frames are relatively long. In financial risk management, scenario analysis is commonly used to estimate changes to a portfolio's value in response to an unfavorable event and may be used to examine a theoretical worst-case scenario. Prior to Shell’s scenario analysis introduction, in 1952, an economist named Harry Markowitz wrote his dissertation on “Portfolio Selection”, a paper that contained theories which transformed the landscape of portfolio management. Since then the most important problem in investment has always been to construct a portfolio of assets which takes both return and risk into proper consideration. A set of holdings must be selected that are designed to conform to the investment objectives and the risk appetite. Crucially this risk appetite is not just expressed in terms of volatility or value-at-risk, but rather in terms of the portfolio’s performance in all foreseeable future states of the markets. <a href="https://nbviewer.jupyter.org/github/JaumeClave/scenario_analysis_and_modern_portfolio_theory_mpt_with_efficient_frontiers/blob/master/scenario_analysis_and_modern_portfolio_theory_with_efficient_frontiers.ipynb" target="_blank"><b>This project</b></a> runs various scenario analyses using “The Greeks” as a basis of portfolio Profit and Loss estimation. It then produces and derives the optimisation problem behind MPT, using the cvxopt package to solve for various efficient frontiers on monthly asset returns and their respective covariance matrices. Various constraints are declared on the solver to satisfy specific market conditions. Special portfolios risk-averse and risk-seeking investors might desire are identified and visualised on the frontier.</p>


<h3 id="networkx-asset-price-correlations">Applying Network Analytics to Visualize ETF Asset Price Correlations</h3>
<p><a href="https://github.com/JaumeClave/asset_price_correlation_NetworkX/blob/master/asset_price_correlation.ipynb" target="_blank">Github</a> 
<a href="https://nbviewer.jupyter.org/github/JaumeClave/asset_price_correlation_NetworkX/blob/master/asset_price_correlation.ipynb" target="_blank">nbviewer</a></p>

<a href="https://nbviewer.jupyter.org/github/JaumeClave/asset_price_correlation_NetworkX/blob/master/asset_price_correlation.ipynb" target="_blank">
<img src="https://jaumeclave.github.io./images/clustured_heatmap.JPG" width="350" align="right"/>
</a>

<p align="justify">“Diversify your portfolio!” Words everyone has heard and a portfolio managers priority. Diversifying methods vary from selecting different asset classes (funds, bonds, stocks, etc.), combining industries, or varying the risk levels of investments. And the most common and direct diversification measurement used in these methods is correlation. Correlation is how closely variables are related and it may be measured with Pearsons correlation coefficient, the degree of linear relationship between two variables. Its values range between -1 (perfect negative correlation) and 1 (perfect positive correlation). While a zero correlation implies no relationship between variables. True diversification is therefore only realistically achieved by investing in assets which are uncorrelated (0) with each other. <a href="https://nbviewer.jupyter.org/github/JaumeClave/asset_price_correlation_NetworkX/blob/master/asset_price_correlation.ipynb" target="_blank"><b>This project</b></a> uses NetworkX and nxviz to investigate and visualize these relationships and investigate price correlations for 39 different assets (currencies, commodities, equities and bonds) with the aim of showing an investor what assets they might need to hold to truly diversify their portfolio.</p>


<h3 id="rfm-clv-customer-segmentation">Retail Customer Segmentation Through RFM and Custmer Lifetime Value Analysis</h3>
<p><a href="https://github.com/JaumeClave/customer_analysis_FRM_CLV/blob/master/direct_marketing_educational_foundation_customer_analysis.ipynb" target="_blank">Github</a> 
<a href="https://nbviewer.jupyter.org/github/JaumeClave/customer_analysis_FRM_CLV/blob/master/direct_marketing_educational_foundation_customer_analysis.ipynb" target="_blank">nbviewer</a></p>

<a href="https://nbviewer.jupyter.org/github/JaumeClave/customer_analysis_FRM_CLV/blob/master/direct_marketing_educational_foundation_customer_analysis.ipynb" target="_blank"> 
<img src="https://jaumeclave.github.io./images/month_on_month_rev.JPG" width="350" align="right"/> </a>

<p align="justify">The dataset that is studied to discover customer insights and how different marketing channels impacts their purchase behavior has been provided by a multichannel company with sales of several hundred million dollars per year. The company has a network of retail stores, a well-established traditional catalog channel and a website. Its brand is very well known nationally (US) and it has a strong positive reputation along with very good long term customer loyalty. The core of the company’s business consists of food products which are often purchased as gifts during the Christmas season. <a href="https://nbviewer.jupyter.org/github/JaumeClave/customer_analysis_FRM_CLV/blob/master/direct_marketing_educational_foundation_customer_analysis.ipynb" target="_blank"><b>This project</b></a> explores this dataset and visualizes key components such as VIP customer spending, marketing channel conversion rate and order method splits before producing a more detailed section on RFM segmentation and the process involving the calculation for customer lifetime value. The data is initially pushed to a local PostgreSQL database and queired using the SQLAlchemy ORM library and Psycopg2  in order to prepare various tables needed for the investifation. RFM segmentation is a great method to identify groups of customers for special treatment because it allows marketers to target specific clusters of customers with communications that are much more relevant for their particular behavior – and thus generate much higher rates of response, plus increased loyalty and customer lifetime value.</p>


<h3 id="networkx-community-detection">Data Clustering and Community Detection in Graphs Using NetworkX</h3>
<p><a href="https://github.com/JaumeClave/community_detection_NetworkX/blob/master/community_detection-networkx.ipynb" target="_blank">Github</a> 
<a href="https://nbviewer.jupyter.org/github/JaumeClave/community_detection_NetworkX/blob/master/community_detection-networkx.ipynb" target="_blank">nbviewer</a></p>

<a href="https://nbviewer.jupyter.org/github/JaumeClave/community_detection_NetworkX/blob/master/community_detection-networkx.ipynb" target="_blank">
<img src="https://jaumeclave.github.io./images/louvian_wttws.JPG" width="350" align="right"/></a>

<p align="justify">Networks are graphs which are made out of nodes and edges and they are present everywhere. Social networks composed of users owned by the likes of Facebook and Twitter contain sensitive relationship data, biological networks help analyse patterns in biological systems, such as food-webs and predator-prey interactions and narrative networks help identify key actors and the key communities or parties they are involved with. The study of a network is essential in order to learn about its information spread, players of influence and its robustness. Networks inherently contain communities, areas of densely connected nodes which provide information about the network, among that information, it allows for the creation of large scale maps of a network since individual communities act like meta-nodes in the network. NetworkX is a Python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks. <a href="https://nbviewer.jupyter.org/github/JaumeClave/community_detection_NetworkX/blob/master/community_detection-networkx.ipynb" target="_blank"><b>This project</b></a> utilises NetwokX to investigate two different networks, studying key centrality measures and utilising the Girvan–Newman and the Louvain Modularity methods to explore network communities.</p>


<h3 id="data-analysis-and-machine-learning-airbnb-new-orleans">Exploring & Machine Learning With Airbnb Listings in New Orleans</h3>
<p><a href="https://github.com/JaumeClave/inside_airbnb_new_orleans_analysis/blob/master/inside_airbnb_new_orleans_analysis.ipynb" target="_blank">Github</a> 
<a href="https://nbviewer.jupyter.org/github/JaumeClave/inside_airbnb_new_orleans_analysis/blob/master/inside_airbnb_new_orleans_analysis.ipynb" target="_blank">nbviewer</a></p>

<a href="https://nbviewer.jupyter.org/github/JaumeClave/inside_airbnb_new_orleans_analysis/blob/master/inside_airbnb_new_orleans_analysis.ipynb" target="_blank">
<img src="https://jaumeclave.github.io./images/new_orleans_neigborhoods_sentiment.JPG" width="350" align="right"/>  </a>

<p align="justify"><a href="https://nbviewer.jupyter.org/github/JaumeClave/inside_airbnb_new_orleans_analysis/blob/master/inside_airbnb_new_orleans_analysis.ipynb" target="_blank"><b>This project</b></a> provides an analysis and evaluation of the current and prospective Airbnb listings in New Orleans (NO), Louisiana. The report intends to contribute information and advice to potential visitors. Methods of analysis include sentiment analysis, data and feature aggregation as well as visualizations such as boxplots, spatial mappings and calendar plots. Other calculations include occupancy rate, prices and trip length averages. Results show that occupancy rate is higher during key dates in NO. In particular, during NOs large events such as the BUKU Music and Art Project and the New Orleans Jazz and Heritage Festival. This produces an increment in property price and demand. The report finds that the prospects of Airbnb in the NO community is positive because of high (+80) review scores across all neighbourhoods and property types. The majority of properties are of type “house” with a categorized size of small and medium, ideal for families and groups of friends. Properties in summer months are comparatively available resulting in a peaceful and quite vacation.</p>


<h3 id="forecasting-lettuce-demand-in-fast-food-resturants">Forecasting Ingredient Demand for Fast Food Resturants in New York and California</h3>
<p><a href="https://github.com/JaumeClave/lettuce_forecast/blob/master/README.md" target="_blank">Github</a></p>

<a href="https://github.com/JaumeClave/lettuce_forecast/blob/master/README.md" target="_blank">
<img src="https://jaumeclave.github.io./images/unnameds-chunk-54-1.png" width="350" align="right"/>  </a>

<p align="justify">Forecasting methods are utilised in all industries. The ability to make predictions of the future based on past and present data and most commonly by analysis of trends is key to success in any market because if done successfully it may drastically reduce costs and increase company revenue and profit. The food industry in this sense, is no different. With ever-changing tastes, tight profit margins, and fickle consumers, the need for accurate projections is an essential component of business success. Industry leaders use state of the art forecasting techniques, centralized data sources and machine learning algorithms to get a step ahead of the competition and to optimally manage their supply chain. In general however, the problem the industry faces lies with scattered data sources, insufficient consideration of external factors, such as campaigns and promotions, moving holidays, weather and ad hoc solutions. <a href="https://github.com/JaumeClave/lettuce_forecast/blob/master/README.md" target="_blank"><b>This project</b></a> forecasts the daily demand for ingredients in a fast-food chain in two different major US markets; New York and California. Each restaurant's historic data is examined and the data is checked for stationarity, transformed and forecasted through an ETS model and a Holt-Winters model. An ARIMA model is also used to forecast ingredient demand in order to test various methods. Finally all three models are evaluated against each other using various estimators of prediction errors and the best is chosen for each individual restaurant location.</p>


<h3 id="Marketing_Resource_Allocation_VAR_&_IRF">Marketing Resource Allocation With Vector Autoregression and Impulse Response Analysis</h3>
<p><a href="https://github.com/JaumeClave/marketing_resource_allocation/blob/master/Marketing%20Resource%20Allocation%20(VAR%20%26%20IRF).ipynb" target="_blank">Github</a> 
<a href="https://nbviewer.jupyter.org/github/JaumeClave/Marketing_Resource_Allocation_VAR_-_IRF/blob/master/Marketing%20Resource%20Allocation%20%28VAR%20%26%20IRF%29.ipynb" target="_blank">nbviewer</a></p>

<a href="https://nbviewer.jupyter.org/github/JaumeClave/Marketing_Resource_Allocation_VAR_-_IRF/blob/master/Marketing%20Resource%20Allocation%20%28VAR%20%26%20IRF%29.ipynb" target="_blank">
<img src="https://jaumeclave.github.io./images/optimal_budget_allocations.JPG" width="350" align="right"/>  </a>

<p align="justify">The 2019 global advertisement budget surpassed $560 billion USD, the US and North-American market, unsurpsignly being the largest spenders. These budgets are stretched among various channels as internet advertising now not only relates to “traditional” Google Ads spending or Facebook Ads spending but to influencer marketing on quickly growing social media apps like Tik-Tok and Snapchat. As new marketing opportunities arise decision makers not only need to figure out how much company resource to devote to their marketing campaigns, they need to decide where exactly to spend that budget. The old axiom, “marketers waste half of their money, but they just don’t know which half” still holds true. <a href="https://nbviewer.jupyter.org/github/JaumeClave/Marketing_Resource_Allocation_VAR_-_IRF/blob/master/Marketing%20Resource%20Allocation%20%28VAR%20%26%20IRF%29.ipynb" target="_blank"><b>This project</b></a> contains a detailed analytical investigation into a retailers marketing budget and it provides an improvement to it by finding its optimal channel allocation. The examination is completed to help the retailer better use their annual marketing budget in order to increase audience reach, conversions and ultimately sales that lead to bottom-line growth. The paper will take a step-by-step approach in solving the optimal resource (channel) allocation problem and will show and explain at each phase what needs to be done to find optimality so that other retailers and companies may adopt the same approach to better allocate their budget.</p>


<details><summary></summary>
  <!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-163462492-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-163462492-1');
</script>
<p>Nothing to see here!</p>
</details>
