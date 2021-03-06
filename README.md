This repository contains various helpful tips and tricks to make JMC development
in Eclipse more pleasant.

## Dynamic Working Sets
JDK Mission Control is quite modular, and it is helpful to use working sets to
help navigate the source. OOMPH has a very nice plug-in for constructing dynamic
working sets. Included in this repo, at workspace/.metadata/.plugins/org.eclipse.core.runtime/.settings/org.eclipse.oomph.workingsets.prefs,
is a useful start set of working sets. 

To use, first install the OOMPH Dynamic Working Sets plug-in into your Eclipse:
https://wiki.eclipse.org/Dynamic_Working_Sets#Download.2FInstallation

Next, copy the org.eclipse.oomph.workingsets.prefs to the appropriate location in your workspace, i.e. &lt;workspace_location&gt;/.metadata/.plugins/org.eclipse.core.runtime/.settings/org.eclipse.oomph.workingsets.prefs, 
or simply copy the contents of the .metadata folder in the repo over to your .metadata folder for you JMC folder.

Once Eclipse have been restarted, you will need to go to Preferences | Oomph / Dynamic Working Sets, and press Apply.
You should now have the working sets available. Try switching the Package Explorer to using the Working Sets as Top Level Elements.