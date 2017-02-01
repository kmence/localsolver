FROM 	airdock/oracle-jdk

RUN 	apt-get update && 	\
	apt install -y 				\
		build-essential	 		\
		wget

RUN	echo $JAVA_HOME && \
	wget http://www.localsolver.com/downloads/LocalSolver_6_5_20160729_Linux64.run && \
	chmod u+x LocalSolver_6_5_20160729_Linux64.run && \
	./LocalSolver_6_5_20160729_Linux64.run

VOLUME /opt/localsolver_6_5/bin
