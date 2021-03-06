### Opportunistic Network

Opportunistic networking is one of the most interesting evolutions of the multihop networking paradigm. opportunistic networks do not consider node mobility a problem but as an opportunity to exploit. In opportunistic networks the mobility of nodes creates contact opportunities among nodes, which can be used to connect parts of the network that are otherwise disconnected. Compare to cloud computing (As shown in fig.1), Opportunistic computing provides an appealing alternative to the mobile computing cloud by allowing devices to join forces and leverage heterogeneous resources from other devices **[1 abstract]**. 

### Mobile Service Composition Challenge

​	First, there exists risk of failure that invoking services provided by mobile users. Due to the limited range of the communication among mobile devices, Tom can only invoke services provided within the required communication distance of the mobile devices. Meanwhile, the other users who are also visiting the gallery keep moving in and out the required distance uncertainly. As a result, there exists risk that the service provider moves out of range when the service is being used, then the composition fails and a recomposition is needed.
​	Second, there is limited work dealing with users’ mobility when making service composition in mobile environment. Then once the generated composition solution fails when the service provider moves out of the required communication distance, it needs to recompose services for the target user.
​	To minimize the risk of composition fails and avoid frequent recomposition, we need to select a service provider with enough availability time for each service such that the composition can exist to finalize. We refer to a composition with such requirement as a risk-aware service composition. The difficulty for it is the mobility of service requesters and providers. For existing selection methods for service composition, only properties of candidate services are considered. But the mobility of service providers and requesters is ignored. Therefore, the risk of failure of the obtained composition is hardly con- trolled. In this paper, we target at solving the RMSC in the above application scenario **[9]**.

### Fitness function
$$
P(csi) = - \sum_{q_t \in Q} \frac{\Delta q_t}{q_{t,max} - q_{t,min}} \\
\Delta q_t = 
\left\{ 
\begin{array}{cc}
qc_t - q_t(csi)  if ... \\
qc_(csi) - qc_t  if ... \\
0 \  else ... \\
\end{array} 
\right. \\
F(csi) = U(csi) + w_{pen} \times gen \times P(csi)
$$
