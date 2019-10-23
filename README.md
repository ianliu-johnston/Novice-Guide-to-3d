# A Novice's guide to SLA 3D Printing Written by a Novice
# Intro 
I was introduced to SLA printing by watching Boulder Creek Railroad youtube videos about diaorama making. Luke Towan was able to create incredibly detailed objects with his 3D resin printer. There's a limit to how small I can sculpt, so I decided to take the plunge and purchase the machine he used, the "Anycubic Photon SLA 3D printer". It was around $300. The process has taken several days, tons of research, more than a dozen failed prints, a 250mL bottle of resin, and a punctured FET. After all that, I have been able to finally create some successful prints. This machine definitely comes with a learning curve, so if a youtube video makes it seem easy, it's because they're already good at generating prints. Keep in mind that the printer itself is easy to use if you keep it clean and maintained, but the way you treat your 3D model will determine the success of your print.
# About
Artist, engineer, maker, etc. 
[Thingiverse Account](https://www.thingiverse.com/Concati)
# Specs
* **Printer**: [Anycubic Photon SLA 3D printer](https://www.anycubic.com/products/anycubic-photon-3d-printer?variant=29419687870524)
* **Resin**: Anycubic 3D printing UV sensitive Resin basic Green 250 mL, UV wavelength 405nm
* Cured via sunlight
* Slicer settings: (software defaults)
  * _Layer thickness(mm)_: 0.05
  * _Normal Exposure time (s)_: 8
  * _Off time (s)_: 1
  * _Bottom Exposure Time(s)_: 50
  * _Bottom layers_: 8
* Build Plate:
   * _Resolution_: 1140 x 2560
   * _X size(mm)_: 68.04
   * _Y size(mm)_: 120.96
   * _Z size(mm)_: 150
   * _Light curing type_: LCD(X direction mirroring)
* Most Used Software:
   * **Slicer**: Anycubic Photon Slicer
   * **Preping the model / adding supports**: [ChiTuBox](https://www.chitubox.com)
   * **3D Modeling**: [Autodesk's Meshmixer](http://www.meshmixer.com/)
# Supporting the 3D objects
Besides creating the 3D object, figuring out how to modify the object is the most difficult aspect of this process. The rest is pretty straightforwards. The best resource I've found for this is 3DPrintingPro's youtube channel playlist: *[ChiTuBox Tutorials](https://www.youtube.com/watch?v=TTZpvhfaNWY&list=PLC4QzbTxrEF-fA1OC_-zE_4f6n1K-w2SS)*. Watch them all twice if you have time.

Some fundamental concepts to keep in mind are: supporting overhangs or islands, orienting the model to have a high center of gravity (prints are made upside down), providing an adequite surface for the model to stick to the build plate, hollowing out solid models, over-supporting the models, orienting the model to have less points of suction then the base, etc.

# Process for Physical Printing
_This assumes a successful build and printer is already setup_
1. Lower build plate to home position
2. Shake resin well and fill resin vat until it is about 3/4 covering the top of the build plate.
3. Insert USB stick and select object to print
4. Go do something else for a while; this is going to take time
5. Don some disposible nitrile or latex gloves. It will be messy
6. Remove the build plate after it stops dripping
7. Scrape model off of build plate
8. Drop model in a bath of isopropyl alcohol.
9. Clean build plate with isopropyl alcohol or window cleaner and replace in its normal position
10. Gently clean model in the alcohol bath. It is advised to use a clear container because afterwards, you can cure the resin in the alcohol, siphon it off and reuse it. Some suggestions for cleaning is to repeatedly dunk it or swirl it in the bath. Another way is with 2 containers you can transfer the alcohol back and forth between containers and pour it over the model in different positions. Another alternative is to swirl it in some alcohol with dissolved resin from previous washes, then in your second container, pour clean alcohol over it. It is advised to use a toothbrush or cheap paint brush to scrub away some of the uncured resin during the alcohol bath.
11. Rinse the model with clean water.
12. Cure the model by placing it in on a window sil or under a UV light, such as a uv nail curing hood or a blacklight. It will be fully cured if the surface is not tacky. If your model is hollow, it is important to make sure the interior of the model is also cured. Drill out any blocked holes if necessary. If the resin is clear or translucent, the inside will cure in bright sunlight. If the resin is opaque, it may be necessary to insert a UV LED into the hole to cure it from the inside.
13. Cleanup your work area. Likely, you have generated quite a bit of dirty paper towels. These can be flattened out, placed into a clear plastic bag and placed on a window sil or under UV light to cure the resin. Liquid resin is extremely toxic and must be disposed of at a hazardous waste facility. It can be stabilized by curing the uncured resin on your waste, then it can be thrown away as normal. Also, if you used a clear glass or plastic container for your alcohol bath, you can also place this in sunlight, and the resin will cure in the alcohol bath. If allowed to settle, the clean alcohol can be siphoned off and reused. 
14. Post-process your model as necessary when it has finished curing. Remove supports, sand, polish, etc.

# List of Tests
_This is also a list of filenames_
1. tireAndCinderblocks
2. stuff
3. witcher
4. articulated_Octopus
5. skeleton_hollowStairs_milkCrates_fork_spacejunk
6. medallion_with_supports
7. PHOTON
8. SkeletonBowman01_with_Supports
9. Fantasy_Castle_And_Dragon
10. tentacles_20joints_4tips
11. stairs_medallion_milk_crate_tests
12. Medusa_and_Skeleton_withSupports
13. medalion_lots_of_support_Castle
14. Fantasy_castle
# Results of first time user for "Anycubic Photon SLA 3D Printer"
## 1st Test: "1_tireAndCinderblocks.photon"
* _Status_: Success
* _total print time_: 43 mins
* _Size_: 3 very tiny objects

Materials printed as expected with great detail. No issues

**post-processing:** minimal post-processing since the supports for the tire were very thin. no supports for the cinderblocks; they were just printed directly on the build plate.

## 2nd Test: "2_stuff.photon"
* _Status_: Epic Fail - object density
* _total print time_: 1hr 2 mins
* _Size_: Huge print that took up most available bed space, but was not very high.

Not enough resin in vat, needed to refill about halfway through.

Many items came out fused together. Density of objects likely too high. Next time need more space between objects.

Strange sheet of resin intersecting a number of objects on the side with the big column.

Some objects at the edges of the print were cut off. Do not go all the way to the edge of the bounding box. Leave some allowance.

detail test for small milk crates (1mm) was successful in that the detail was captured, but the walls were too thin and the cured resin was brittle. The object fell apart during washes. The next to largest milk crate has the same issue.

gear needed supports

area between cup and fork and bed with strange stringy pattern. looks like rim of cup was repeated a few times.

**post-processing:** Managed to salvage some items such as the chairs, the escher puzzle piece, some cinderblocks, the toppled column. 

## 3rd Test: "3_witcher.photon"
* _Status_: Fail - build plate adhesion
* total print time: 2 hrs 1 mins
* _Size_: medium sized object

Did not stick to the plate and instead stuck on the bottom of the resin vat. Need to scrape it off and in the process, knicked the FEP and had to change it out. Possible reasons for getting stuck on the bottom are: additional things from the last print getting stuck to the bottom of the vat, or the suction was too great on the bottom of the vat and unstuck it from the build plate.
Additionally, I did not add supports to this object. Will try again with the same print.

**post-processing:** No post-processing needed

## 4th Test: "4_articulated_Octopus.photon"
* _Status_: Fail - build plate adhesion
* _total print time_: 2 hrs 1 mins (Aborted)
* _Size_: medium head; many small parts

Stopped the print in the middle of the head because around 60% of the small pieces stuck to the bottom of the vat. The small pieces did not have supports.

The medium sized piece, the head did not stick and would probably have turned out well if I had not aborted the print. Supports were used, but some supports were in the ball joints. Need to be more careful about that next time.

**post-processing:** Some supports for the octopus head were inside of the ball joint, rendering them unusable. Since the joints were printed directly on the build plate, no post-processing required. However, when I attempted to fit them together, most of them broke.

## 5th Test: "5_skeleton_hollowStairs_milkCrates_fork_spacejunk.photon"
* _Status_: Fail - build plate adhesion
* _total print time_: 2hrs ish (Aborted)
* _Size_: All objects sized differently

All objects had added supports, esp. the skeleton. Smaller objects were placed slightly farther away from each other this time. Scraped the bottom of the vat to remove the solid bits of resin. Supports generated in photon slicer software.

Around 15 minutes in, heard some noises coming from the printer (I though it was the cup moving in the wind.). Turned out to be the build coming off of the build plate. Due to the fact that they were all on the same base layer of resin, all objects came off because the space junk was stuck to the bottom of the vat. Build was stopped around 2 hrs in && sheet was thrown away. To prevent one failing object from disturbing the rest of the print, each object should have their own separate raft and should not share a common raft.

(EDIT ^^) the noise from the printer is the build sticking to the FET and snapping it back like a drum. Probably a good noise because it means the build is sticking to the build plate.

**post-processing:** No post-processing needed

## 6th Test: "6_medallion_with_supports.photon"
* _Status_: Fail - build plate adhesion
* _total print time_: 2 hrs 1 mins
* _Size_: medium sized object

Repeat of 3rd Test, but this time, object is hollowed out, rotated 15 degrees on the X axis and supports generated in "Autodesk's Meshmixer"

object did not stick to the build plate.

**post-processing:** No post-processing needed

## 7th Test: "PHOTON.photon"
* _Status_: Success
* _total print time_: 5 hrs 3 min
* _Size_: Large but strandy

Default generic print that comes with the slicer software. Came out very well. No complications or supports needed.

**post-processing:** No post-processing needed

## 8th Test: "8_SkeletonBowman01_with_Supports.photon"
* _Status_: Fail - build plate adhesion
* _total print time_: 1 hr 35 mins
* _Size_: large

Model did not stick to build plate.

**post-processing:** No post-processing needed

## 9th Test: "9_Fantasy_Castle_And_Dragon.photon"
* _Status_: Partial Success - build plate adhesion
* _total print time_: 3hr 55min
* _Size_: 2 Large objects

Castle stuck to the build plate && print was successful. Model was upright with minimal supports that were made in anycubic slicing software.

Supports for dragon were too thin and it broke off of the raft, but this did not affect printing the castle. The raft and very thin supports were still stuck to the build plate.

The rafts were not close to each other at all.

**post-processing:** Castle was exceedingly easy to clean up. Will try another print without any supports.

## 10th Test: "10_tentacles_20joints_4tips.photon"
* _Status_: Partial Success - build plate adhesion
* _total print time_: 43 mins
* _Size_: Many small objects

Generated supports in ChiTuBox software, verified print in PreForm, then sliced with anycubic slicer software.

Of the 20 joints, only 5 came out. The rest stuck to the bottom of the vat, or the supports could not hold them onto the raft. Of the 4 tips, only 1 came out. All of them were on the back row.

**post-processing:**

## 11th Test: "11_stairs_medallion_milk_crate_tests.photon"
* _Status_: Fail - build plate adhesion
* _total print time_: 1hr ish aborted
* _Size_: One large object, one medium object and three small objects

All objects except for one basket did not stick to the build plate.

Going through some video tutorials from "3DPrintingPro" on Youtube led me to believe that the raft itself may have been causing a problem. What I noticed on the models is that the very base of the object was narrower than the upper parts of the raft, and that's where the object unstuck from the plate. My guess is that the greater surface area of the upper lip of the raft caused more suction against the bottom of the vat than the base of the object had on the plate.

**post-processing:** No post-processing needed

## 12th Test: "12_Medusa_and_Skeleton_withSupports.photon"
* _Status_: Partial Success - build plate adhesion
* _total print time_: 2hr 35min
* _Size_: two medium objects

Skeleton warrior was successful. Base was relatively easy to take off of the build plate.

Medusa bust was unsuccessful. Model unstuck from build plate. Evidence that it got past the supports and base, but might not have had enough support on the back of the head.

**post-processing:** Rear foot broke off during support removal. Support system was successful in preserving the details of the model, but some of the contacts were far too thick and fused to some parts of the model. For example, the mouth and rear foot was fused completely with the supports. TODO: Try to revise this print with fewer supports.

## 13th Test: "13_medallion_more_supports_base.photon"
* _Status_: Success
* _total print time_: 2hrs 9min
* _Size_: large object

Medallion printed successfully. One side of the base was still coming off of the build plate, but the print itself is clean.

**post-processing:** Placement of supports was so dense that many places were fused together. At the pointy edges of the object, the density of supports was so great that when cutting them off, they took the pointy bit with it for some sides. Support placement at the medallion ring was easy to remove. Holes had been plugged, preventing uncured resin from escaping. Drilling them out was necessary. At the same time, used the drill bit to remove some of the internal supports through the holes. The back of the object was warped and jagged after removing the supports. Rough handling during drilling and support removal broke off or chipped all but 2 teeth.

## 14th Test: "Fantasy_castle.photon"
* _Status_: Experiment
* _total print time_: 1hrs 17min (Prematurely aborted)
* _Size_: large object

Testing how much of this model would be possible to print with resin barely covering the bottom of the vat. 30% complete before there is no available resin. See picture.

**post-processing:** No post-processing needed


# Lessons
1. Build plate adhesion

    _Adequite build plate adhesion is essential to successful prints._ 

    Adhesion failure may be due to a number of factors: 
    * suction to bottom of resin vat
    * improperly supported overhangs
    * top-heavy models
    * cured or partially cured material that has been stuck to the FET or is floating in the liquid resin
    * build plate has not been properly cleaned
    * FET has been knicked and the cured resin is catching on it

    Adhesion problems are indicative of a number of other issues

2. Properly supported models

    Manually placed supports are necessary for complex models. Autogenerated supports may not be required for simpler models, though further experimentation is required.

# Troubleshooting
## Cleanup after Failed Prints
This is the most common failure and is tedious, but essential. **If you had a failed print, you must clean out your resin vat or it may fail any future print.** 
1. Remove the resin vat
2. Pour liquid resin through a filter into a container (Don't want any solid chunks in the resin)
3. Gently scrape any stuck resin off of the FET. **Be aware that you can easily ding, knick, gouge or puncture the FET at this stage.** It is suggested to gently press the bottom of the FET to try to break the suction, then use the scraper to pop it off.
3. Clean the resin vat thoroughly with isopropyl alcohol or window cleaner and paper towels.
4. Clean the LCD Screen with window / glass cleaner. **If the LCD screen has an excessive amount of resin on it, inspect the FET for holes.** If the FET has a hole, it definitely needs to be changed because liquid resin can leak onto the LCD screen and cure, thus failing every future print.
6. Replace resin vat and tighten both screws with the same pressure.


# Resources
## Software
* [Free Meshmixer software from Autodesk (The "Photoshop" Of 3D printing)](http://www.meshmixer.com/)
* [Free ChiTuBox for generating supports and rafts](https://www.chitubox.com)
* [Free Formlabs Preform software (Will not export STL's but useful for verifying if your model supports are going to print successfully)](https://formlabs.com/software/)

## Resins
* [Google sheet for looking up custom settings for various resins of different brands](https://docs.google.com/spreadsheets/d/1crvzMnt_8NJXAsABinoIhcOjE8l3h7s0L82Zlh1vkL8/edit#gid=0)

## How To's
* [Excellent guide to anycubic photon](https://github.com/Photonsters/anycubic-photon-docs/blob/master/FAQ.md)
* [Boulder Creek Railroad overview](https://www.youtube.com/watch?v=1tnDItw0ZLc)
* [3d print farm youtube channel](https://www.youtube.com/channel/UC5k3TJL8ud4jh7863gjywPQ/videos)
* *[ChiTuBox Tutorials from 3DPrintingPro on Youtube](https://www.youtube.com/watch?v=TTZpvhfaNWY&list=PLC4QzbTxrEF-fA1OC_-zE_4f6n1K-w2SS)*: These videos are incredibly helpful
* [Post processing models](https://www.3dhubs.com/knowledge-base/post-processing-sla-printed-parts/)

## Information about SLA printing
* [Adding supports for 3d printing](https://www.3dhubs.com/knowledge-base/supports-3d-printing-technology-overview/#sla-and-dlp)
* [Overview for stereolithography (SLA) printing from formlabs](https://formlabs.com/blog/ultimate-guide-to-stereolithography-sla-3d-printing/)
* [Another overview for SLA from 3dhubs.com](https://www.3dhubs.com/knowledge-base/introduction-sla-3d-printing/) Interesting quote:
_In bottom-up SLA printers, things are more complicated. Overhangs and bridges still need to be supported, but minimizing the cross-sectional area of each layer is the most crucial criterion: the forces applied to the part during the peeling step may cause it to detach from the build platform. These forces are proportional to the cross-sectional area of each layer. For this reason, parts are oriented in an angle and the reduction of support is not a primary concern._

## Troubleshooting 3D models
* [Fixing non-manifolds](http://3dprintingninja.blogspot.com/2014/12/non-manifolds-automatic-fixing-methods.html)
