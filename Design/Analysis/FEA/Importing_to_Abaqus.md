To Input a solid model from SolidWorks to Abaqus:

[*http://www.intrinsys.com/blog/2016/importing-parts-into-abaqus-cae*](http://www.intrinsys.com/blog/2016/importing-parts-into-abaqus-cae)

For individual parts:

-Open part in solidworks (convert to MKS if necessary, makes it easier for some material properties if they cannot be easily acquired in IPS)

-Save file as ACIS SAT (.sat) in correct folder easily accessible through Abaqus, this can be confusing at times)

-Open Abaqus, go to File -&gt; Import

> -select Part
>
> -check the box to make complete solid
>
> -on the top tabs, select scaling..Abaqus apparently does not handle scaling very well, if part was saved in MKS abaqus read that as MMGS for my first couple imports..was necessary to scale all dimensions to .001
>
> -done! Part with geometry is now accessible to run simulations in abaqus
>
> -general FEA analysis procedure required (adding material properties, sections, instances, BCs etc…)
>
> -There is a possibility to pull entire assemblies, as well as maintaining material properties etc from SolidWorks...will update as I continue to do research

Full water tank heat xfer transient tutorial

[*https://www.youtube.com/watch?v=7vdnTO2RS2Q*](https://www.youtube.com/watch?v=7vdnTO2RS2Q)
