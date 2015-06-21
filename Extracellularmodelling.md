---
layout: index
---

# Inferring neural activity from extracellular potentials


{% comment %}	
	#!div style="float:right;width:235px;"
	[[Image(single-unit.jpg,width=200)]]
	_Extracellular recording of a single neuron._
{% endcomment %}
	
A lot of new insight into how single neurons function and process information has been obtained the last decades. A central experimental technique behind this new understanding is the recording of neural electrical activity by means of various types of electrodes. In typical extracellular recordings of neurons firing action potentials, thin and sharp electrodes are placed next to the soma of the cell in question. Characteristic voltage traces reflecting ion currents through the cell membrane of the soma and nearby dendrites give a reliable measure of its firing activity. In alternative intracellular recordings the electrode penetrates the cell membrane, and the voltage jump across the membrane, i.e., membrane voltage is measured directly.

Action-potential firing of individual cells can be measured directly using both extracellular and intracellular recordings electrodes. However, one would also like to measure other aspects of neural activity such as the dendritic processing of numerous spatially distributed synaptic inputs onto a neuron. Such activity also produces extracellular potentials, _local field potentials (LFP)_, which is picked up by standard electrodes. The interpretation of such data in terms of its specific neural origin is generally more difficult. The main reason is that electrical activity reflecting dendritic processing typically is spatially more spread out than for action potentials where currents close to soma dominate. Also, while action-potentials are fast events which only last for a few milliseconds and have a rather standard temporal extracellular signature, the bombardment of dendrites by synaptic inputs is more continuous and may lack clear reproducible patterns. To extract more information about neural activity various types of multielectrodes are now also used. In such electrodes the extracellular potentials are simultaneously recorded at several spatial positions, and more data which can be used in an interpretation thus becomes available.

{% comment %}
[[Image(laminar-electrode.jpg,width=80%)]]

_Illustration of the layered structure of cortex. The laminar electrode penetrating the six cortical layers with different neuronal populations is illustrated on the right. Three cortical populations are included in the illustration, pyramidal cells in layers 3 [red] and 5 [green] and stellate cells in layer 4 [blue]._
{% endcomment %}

In our group we are working with several projects related to the question of relating extracellularly recorded potentials to the underlying neural activity:
   * understanding the biophysical origin of the extracellular signature of action potentials (spikes) 
   * understanding the biophysical origin of the local field potential 
   * generation of test-data for validation of automatic spike-sorting algorithms
   * methods for analysing LFP data (in particular _inverse current source density (iCSD)_ method)
   * methods for jointly analysing MUA and LFP data (in particular _laminar population analysis (LPA)_ 
   * understanding and interpreting potentials recorded in multielectrode arrays (MEAs)  



## Publications

* G.T. Einevoll, C. Kayser, N. Logothetis, and S. Panzeri: _Modeling and analysis of local field potentials for studying the function of cortical circuits_, Nature Reviews Neuroscience 14:770-785 (2013). ([www](http://www.nature.com/nrn/journal/v14/n11/full/nrn3599.html)) 
* S.Leski, H. Linden, T. Tetzlaff, K.H. Pettersen, and G.T. Einevoll: _Frequency dependence of signal power and spatial reach of the local field potential_, PLoS Computational Biology 9:e1003137 (2013). ([www](http://www.ploscompbiol.org/article/info%3Adoi%2F10.1371%2Fjournal.pcbi.1003137))
* A. Devor, P.A. Bandettini, D.A. Boas, J.M. Bower, R.B. Buxton, L.B. Cohen, A.M. Dale, G.T. Einevoll, P.T. Fox, M.A. Franceschini, K.J. Friston, J.G. Fujimoto, M.A. Geyer, J.H. Greenberg, E. Halgren, M.S. Hamalainen, F. Helmchen, B.T. Hyman, A. Jasanoff, T.L. Jernigan, L.L. Judd, S.-G. Kim, D. Kleinfeld, N.J. Kopell, M. Kutas, K.K. Kwong, M.E. Larkum, E.H. Lo, P.J. Magistretti, J.B. Mandeville, E. Masliah, P.P. Mitra, W.C. Mobley, M.A. Moskowitz, A. Nimmerjahn, J.H. Reynolds, B.R. Rosen, B.M. Salzberg, C.B. Schaffer, G.A. Silva, P.T.C. So, N.C. Spitzer, R.B. Tootell, D.C. Van Essen, W. Vanduffel, S.A. Vinogradov, L.L. Wald, L.V. Wang, B. Weber, and A.G. Yodh: _The challenge of connecting the dots in the B.R.A.I.N._, Neuron 80:270-274 (2013). ([www](http://www.cell.com/neuron/retrieve/pii/S0896627313008064))
* S.L. Gratiy, K.H. Pettersen, G.T. Einevoll, and A.M. Dale: _Pitfalls in the interpretation of multielectrode data: on the infeasibility of the neuronal current-source monopoles_, Journal of Neurophysiology 109:1681-1682 (2013.) ([www](http://jn.physiology.org/content/109/6/1681.long))
* G.T. Einevoll, H. Linden, T. Tetzlaff, S. Leski, and K.H. Pettersen: _Local field potential: biophysical origin and analysis'', in ''Principles of Neural Coding_, edited by R. Quian Quiroga and S. Panzeri, pp. 37-59, CRC Press (2013). 
* K.H. Pettersen, H. Linden, A.M. Dale and G.T. Einevoll: _Extracellular spikes and CSD'', in ''Handbook of Neural Activity Measurement_, edited by R. Brette and A. Destexhe, pp. 92-135, Cambridge University Press (2012). [http://arken.umb.no/~gautei/forskning/PettersenLindenDaleEinevoll-BookChapter-revised.pdf [preprint, PDF, 5604kB]]
* G.T. Einevoll, F. Franke, E. Hagen, C. Pouzat, and K.D. Harris: : _Towards reliable spike-train recordings from thousands of neurons with multielectrodes_, Current Opinion in Neurobiology 22:11-17 (2012). ([www](http://www.sciencedirect.com/science/article/pii/S0959438811001565)) 
* S.L. Gratiy, A. Devor, G.T. Einevoll, A.M. Dale: _On the estimation of population-specific synaptic currents from laminar multielectrode recordings_, Frontiers in Neuroinformatics 5:32 (2011)([www](http://www.frontiersin.org/neuroinformatics/10.3389/fninf.2011.00032/abstract))
* H. Linden, T. Tetzlaff, T.C. Potjans, K.H. Pettersen, S. Gruen, M. Diesmann, and G.T. Einevoll: _Modeling the spatial reach of the LFP_, Neuron 72:859-872 (2011 ([www](http://www.cell.com/neuron/abstract/S0896-6273%2811%2901005-1))
* S. Leski, K.H. Pettersen, B. Tunstall, G.T. Einevoll, J. Gigg, and D.K. Wojcik: _Inverse Current Source Density method in two dimensions: Inferring neural activation from multielectrode recordings_, Neuroinformatics 9:401-425 (2011) ([www](http://www.sciencedirect.com/science/article/pii/S1468121811001039)) [http://www.youtube.com/watch?v=kGA9T6wtXBQ  [supplementary video on YouTube]]
* G.T. Einevoll, D.K. Wojcik, A. Destexhe: _Modeling extracellular potentials_, Journal of Computational Neuroscience 29, 367-369 (2010) [http://www.springerlink.com/content/gh40081608167487/ [full-text link]]
* H. Linden, K.H. Pettersen, and G.T. Einevoll: _Intrinsic dendritic filtering gives low-pass power spectra of local field potentials_, Journal of Computational Neuroscience 29, 423-444 (2010) [http://www.springerlink.com/content/w0255067152570h0/ [full-text link]]
* F. Franke, M. Natora, P. Meier, E. Hagen, K.H. Pettersen, H.Linden, G.T. Einevoll, and K.Obermayer: _An automated online positioning system and simulation environment for multi-electrodes in extracellular recordings_, in Proceedings of the 32nd Annual International IEEE EMBC Conference, Buenos Aires, Argentina, 2010 [http://arken.umb.no/~gautei/forskning/PosiEMBC-reprint.pdf [reprint, PDF, 494kB]]
* G.T. Einevoll: _Modeling of extracellular potentials recorded with multicontact microelectrodes_, in Proceedings of 7th Int. Meeting on Substrate-Integrated Microelectrodes, Reutlingen, Germany, 2010 [http://arken.umb.no/~gautei/forskning/Einevoll_MEA_2010.pdf [preprint, PDF, 522kB]]
* P. Blomquist, A. Devor, U.G. Indahl, I. Ulbert, G.T. Einevoll, and A.M. Dale: _Estimation of thalamocortical and intracortical network models from joint thalamic single-electrode and cortical laminar-electrode recordings in the rat barrel system_, PLoS Computational Biology 5, e1000328 (2009).[http://www.ploscompbiol.org/article/info%3Adoi%2F10.1371%2Fjournal.pcbi.1000328;jsessionid=A59F299D014DBA326D01BF3C256B9C6F [full-text link]]
* K.H. Pettersen and G.T. Einevoll: _Neurophysics: what the telegraphers equation has taught us about the brain_, in "An anthology of developments in clinical engineering and bioimpedance: Festschrift for Sverre Grimnes", edited by Ø. Martinsen and Ø. Jensen (Unipub, Oslo, 2009). [http://arken.umb.no/~gautei/forskning/PettersenEinevoll-Grimnes70-February2009.pdf [preprint, PDF, 465kB]] 
* K.H. Pettersen, E. Hagen and G.T. Einevoll: _Estimation of population firing rates and current source densities from laminar electrode recordings_, Journal of Computational Neuroscience 24, 291-313 (2008). [http://www.springerlink.com/content/513k30u3q623l19w/?p=d55f4b42566e41b3b50712616e36cdfc&pi=24 [full-text link]]
* K.H. Pettersen and G.T. Einevoll: _Amplitude variability and extracellular low-pass filtering of neuronal spikes_, Biophysical Journal 94, 784-802 (2008). [http://www.biophysj.org/cgi/content/full/94/3/784 [full-text link]]
* G.T. Einevoll, K.H. Pettersen, A. Devor, I. Ulbert, E. Halgren, A.M. Dale: _Laminar Population Analysis: Estimating firing rates and evoked synaptic activity from multielectrode recordings in rat barrel cortex_, Journal of Neurophysiology 97, 2174-2190 (2007). [http://jn.physiology.org/cgi/content/full/97/3/2174 [full-text link]]
* K. Pettersen, A. Devor, I. Ulbert, A.M. Dale and G.T. Einevoll: _Current-source density estimation based on inversion of electrostatic forward solution: Effects of finite extent of neuronal activity and conductivity discontinuities_, Journal of Neuroscience Methods 154, 116-133 (2006) [attachment:pettersen-2006JNSM-iCSD.pdf [reprint, PDF, 1027kB]]



