# vrmlHouseOfImmersion
A repository for a historically interesting file we created at NIST to help test VRML1 plugins and browsers. We are resurrecting it in multiple formats for use by the web graphics (or anyone else) community.

The comments of the top of the original file state:
```javascript
#VRML V1.0 ascii
#House of Immersion Revision History
# 11/9/95 validated - Sandy
Separator {
	Separator {
		DEF Viewer Info {
			string "walk"
		    }
		DEF Title Info { string "The House of Immersion" }
		DEF SceneInfo Info {
		    string
"The VRML House of Immersion was created by:
Sandy Ressler (still at NIST)
Christine Piatko (at NIST)
it was based on the original Virtus Walkthrough
and Inventor versions by:
Sharon Davison (now at Microsoft)
Mark Pflaging  (now at GWU)
and
Alan Sun (now at MIT).
```

Organizational affiliations mentioned in the above comments are far out of date.

Other file format conversions of this file will be added. 

## Conversion to VRML2 (also commonly called VRML97)
The original VRML1 file format is now quite difficult to work with, not much reads it.
In order to do much of anything it's wise to convert to VRML2 and go from there. To convert from VRML1 to VRML2 there is a useful
utility (we think created by SGI) at the page: http://www.interocitors.com/polyhedra/vr1tovr2/index.html

Download the zip file linked to on that page and execute on a PC. The executable takes 2 arguments inputfile and outputfile.
To execute: vrml1tovrml2 inputVRML1File outputVRML2File

The result of this execution is include in this repository as vrml2HouseOfImmersion.wrl
