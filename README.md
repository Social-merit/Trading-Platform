Trading-Platform 
================  
This project is the most awaited project in open source community where every user who belongs to Stock Trading always wanted to develop its own software. This project has been developed specifically for Indian Market Stock Trading. It encompasses end to end trading cycle for intraday trading but the design would  be such that it can be easily extended for delivery trading. During the lifecycle of this project we will be using most advance technologies but the base code will always be C/C++.  


Development Methodology: 
======================== 
We use "Incremental Life Cycle Model" along with Cross-Platform Development (Portable).  


Project Priorities and Assumptions: 
=================================== 
1) Low Latency, High Performance all the time. 
2) Wherever choice has to be made between memory and execution speed, we give preference to speed. 3) Every module 
   devloped will be exhaustively tested.   


How the work Proceed: 
===================== 
Before the beginning of any new project, we should know the "PROBLEM STATEMENT", so here it is    

	"Problem Statement"   
	-------------------   
	To Build a high performance, low latency, end to end Trading Platform for Indian Stock Market but not limited to which   home users should be able use for trading which guarantees (99% of the times) the profit but does not guarantees 
	maximized profit for intraday trading.  
    
	First Step:   
	-----------   
	To provide the optimal solution to any problem is "UNDERSTAING THE PROBLEM".   
	To understand the above problem statement you need to really extract the explicit and implcit requirements from the 
	statement. Here is the List of requirements:  
	
		Explicit:         
		---------               
			1)  High Performance               
			2)  Low-Latency               
			3)  End-to-End Trading Platform               
			4)  Focus on Indian Stock Market but not limited to it.               
			5)  Guarantees (99% of the times) the profit but does not guarantees maximized profit.               
			6)  Only for Intraday Trading.                        
		Implicit:         
		---------               
			1)  Book Keeping of the order and trade (Order Management System).               
			2)  Availability of Market Data to End-Users on Demand for identifying the stock and placing the order.
			3)  User Account Management.                              
	
			Might be I missed something please suggest and after reveiw we add it here.                  

	Second Step:   
	------------   
	To understand the above Explicit/Implicit requirements, you should have the "KNOWLEDGE OF VARIOUS TECHNOLOGIES" and 
	indepth undertstanding of the "PROBLEM DOMAIN" i.e. Stock Market. Once this is achieved we need to architect the 
	solution in terms of Software and Hardware nodes and their integration.      

	Third Step:   
	-----------   
	To solve the problem statement, the above requirements should be "DECOMPOSED IN MODULES" and map to them with 
	technolgoies/software/hardware used. Below is the list of modules we are 
	able to identify:              

		Modules Included:       
		-----------------         
			Core Modules:         
			--------------       
			1)  Core Libraries       
			2)  Manual Order Entry System       
			3)  Auto Order Entry System       
			4)  Artificial Exchange       
			5)  Algorithmic Trading Platform       
			6)  Smart Order Router       
			7)  Direct Trading Platform (Ooptional)                
			
			Utility Modules:         
			----------------       
			8)  Logger Server       
			9)  HeartBeat Server    

             
		Technologies Used:       
		------------------
		   Software:        
		   ---------     
				We always use freeware, Open Source Softwares or APIs which are the part of GPL, LGPL.xx licence.         
				Any special requirement for building/using the modules will be detailed in specific module.                
		
				For development, we generally use: 
				----------------------------------        
					Windows-7 for Operating System but any other OS ca be used. Our Code is Platform Indepandant.        
					Visual Studio 2013 in built compiler for build                    
								              or         
					Intel@ Compilers which can be easily integrated with Visual Studio IDE.  
					
				For real time, we generally use:
			  --------------------------------        
					Linux-susse 10 or above with real time extensions.        
					gcc 4.4.1 for build.        
					vi editor                

			Hardware:        
			---------        
				No special requirement for development purpose.        
				For real time use, it depands how much Stock you are interested in and the various configuration of modules.         
				We prefer generally the below configuration for any number of Stock Trading:         
				256 GB RAM          
				16 core processor         
				1 TB of HDD/SDD                  

			Programming Languages and other Technologies:        
			---------------------------------------------        
			  C, C++99/c++11, Lua, ZeroMq, nanodbc, Lock-Free Data Structures, Intel TBB, Boost, Google Protobuf, MySql,   
			  Python.           

	Fourth Step:   
	------------   
	Decompose each module till it becomes entity to provide the useful functionality. We are going to explain this in each   module detailed section.      

	Fifth Step:   
	------------   
	We do design/develop/benchmark/unit test/integration testing of the above modules.      

	Sixth Step:   
	------------   
	We deploy the delivered software on various hardware nodes as per the deployment architecture and integrate them.      

	Seventh Step:   
	------------   
	Observe the behaviour of deployed software on live traffic and cut two branches at this level : 
	1st branch continue to do incremental development and 
	2nd branch fix the issues reported which can be later merged with 1st branch for another release.      


Any suggestions for improvement are most welcome.   
