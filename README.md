# ReflectionMachine

This repo contains the results of the thesis 'The Functional Preference of Policemen when Using a Reflection Machine in Preventive Frisking'.

First, we included the application ('Application_RM.zip') implemented by Anaïs de Graaf and adjusted by Hannah Venhuizen.
This application can be used in English or Dutch. Currently, the settings are in English. If it is desired to change this, you need to alter the file "interface.xml":
<ol>
	<li> Line 21 → change fx:controller="nl.ru.ai.fm.Controller" to fx:controller="nl.ru.ai.fm.Controller_nl" </li>
	<li> Line 43 & 65 → change text="because:" to text="omdat:" </li>
	<li> Line 114 → change 'I don't know' to 'Weet ik niet' </li>
</ol>

Second, it contains an html file constructed from a jupyter notebook including a result analysis of the data. In this notebook, both the data of the survey and application is included. Please note that this notebook is mainly used in order to order the data to write the thesis and is not written in a very formal way, it is mostly background information. The original notebook (i.e. .ipynb file) could be provided if necessary.

Third, it contains two excel files ('StudentExperiment.xlsx' and 'AgentExperiment.xlsx') in which the data is included, one for the student participants and one for the policemen.
Both the files contains both the raw data and the translated data. An information sheet is included to provide information about the tabs.

Finally, it contains the txt files which are the direct output of the application.
This can be found in the folder 'output_app'. The first letter indicates whether it was a student (s) or a policeman (p), then p* indicates which participant it points to, then _** represents the design format.
	where 
<ul>
  <li>a1 := informed about DSS, with order part A -> part B</li>
  <li>a2 := informed about DSS, with order part B -> part A</li>
  <li>b1 := NOT informed about DSS, with order part A -> part B</li>
  <li>b2 := NOT informed about DSS, with order part B -> part A</li>
</ul>