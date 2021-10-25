# Hurricane wind field modeling
## Gradient wind speeds
Hurricane gradient wind speeds in every 10 minutes are generated based on Georgiou (1986)'s gradient wind field model and the hurricane catalog developed by Fangqian Liu (2014). Examples of hurricane tracks are shown in the following figure:  
![Alt text](/assets/Figure1.jpg?raw=true "Hurricane tracks")  
An example of the calculated gradient wind speeds is shown as follows:  
![Alt text](/assets/Figure2.jpg?raw=true "Hurricane wind fields (m/s)")  
## Surface wind speeds
Surface wind speeds at 10 meters height are calculated considering the gradient-surface transition and sea-land transition suggested by Vickery et al. (2009a). As an testbed, Massachusetts is divided into a set of grids and surface wind speed and direction records are calculated for each grid.  
![Alt text](/assets/Figure3.jpg?raw=true "Grids of Massachusetts")  
The calculated wind speed and direction records of a grid and the corresponding hurricane track is shown here. Note that hurricane winds are considered only when the location of interest is within 250 km of the hurricane eye according to Vickery et al. (2009b).  
![Alt text](/assets/Figure4.jpg?raw=true "The hurricane track within 250 km of the location of interest")  
![Alt text](/assets/Figure5.jpg?raw=true "Wind speed and direction records")  
![Alt text](/assets/Figure6.jpg?raw=true "Wind speed in North and East directions")  

References:  
Georgiou, P. N. (1986). Design wind speeds in tropical cyclone-prone regions. Ph.D. dissertation. University of Western Ontario, London, Ontario, Canada.  
Liu, F. (2014). Projections of future US design wind speeds and hurricane losses due to climate change. Ph.D. dissertation, Clemson Univ., Clemson, SC, USA.  
Vickery, P. J., Wadhera, D., Powell, M. D., & Chen, Y. (2009). A hurricane boundary layer and wind field model for use in engineering applications. Journal of Applied Meteorology and Climatology, 48(2), 381-405.  
Vickery, P. J., Wadhera, D., Twisdale Jr, L. A., & Lavelle, F. M. (2009). US hurricane wind speed risk and uncertainty. Journal of structural engineering, 135(3), 301-320.