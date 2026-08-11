# Collection

I have an HTML file that prepares Pokemon Quest models for 3d printing in 3mf format. When I download the Ho-oh .3mf file, in Bambu Studio I get the error message: Object name: Ho-Oh
Size: 65.16 × 39.7 x 50 mm
Volume: 10941.7 mm*
Triangles: 6854
Error: 1 non-manifold edge
Tips:
To repair the model, please use a third-party tool before importing it into Bambu Studio, such as https://www.formware.co/onlinest/repair.
I tried to fix this issue with another AI and the 3mf file for Ho-oh does not look good - there are different colors at the top of each area (I suspect the issue is 13 of 170 cap patches (about 1 per hole. It should patch the color-selection logic to use a majority vote across the whole hole boundary instead of just the first edge) get the wrong color because the code only looks at one arbitrary boundary edge instead of the whole hole. Let me fix it with a proper majority vote.). 
Please reassess this whole project: When I add the 3mf file into Bambu studio, it says it is not created by Bambu Labs import geometry and color data only. Would it be better if it was a STL file? - I have to go into the Print Plate screen to assign colors and on the left side during the normal view there is no dropdown under the model to select colors - is this correct?
