> Most concepts of vision propose, explicitly or implicitly, that successful visual behavior depends on recovering the sources of stimulus features either directly or by a process of statistical inference. However, given the inability of the visual system to access the physical properties of the world, these conceptual frameworks cannot account for the behavioral success of biological vision. The current convolutional neural network are based on the same methodology. They only have access to the final image. 

>"Quantifier to a perception Module" -HA

The current CNN systems are based on quantification of the image, the physical properties of interpretation is rather subjective. What is perceived is based on experience, and is subjective. The closed system of human environment (i.e. we all exprience the surroundings almost the same -- flowers, books, tables, animals, 3D object primitives) might be the very reason we are unable to unite perception and quantification at the human level; as on a higher level we all share an almost similar experience.

>The alternative is that the visual system automatically links simple, recurrent stimulus patterns with reproductive success, without ever recovering real world properties. This strategy provides a different way of studying the relationship between the objective world and subjective experience, and offers a way of understanding the operating principles of visual circuitry without invoking feature detection, image representation in the brain, and/or probabilistic inference.

# Module 1, Background: What we actually see
1. Perception: What we are aware of what we see.
2. Physical measurements: simple tools that physicists and business scientists have been making and that can measure objectively.
3. Psychophysical measurements: Done with comparative measurements. (Subjective measures) eg: Set a standard stimulus and let observers match it with their own stimulus. 

## The strange way we see the physical world:
1. Angles
2. illuminance
3. geometry
4. colour

## "The inverse problem"

###The inverse problem in illuminance:
Dr. Purves says it is impossible to find the individual contribution of:
-1. illumination
2. reflectance
3. transmittance
in the final retinal stimulus, i.e. it is impossible to find their individual roles in generating the stimulus received by the retina. 

![](/VPBImages/luminanceInverse.png/)
## The inverse problem in geometry
 ![](/VPBImages/geoInverse.png/)
 
Similar problems exist for both motion and color perception, and the retinal stimulus.

> Physical devices use physical measurement to measure the physical reality. But our eyes don't measure physical reality; and in that sense the real world is just unknowable. In some ways, we behave correctly, so we know it works.
## Visual Stimuli
Light means the part of the spectrum, human beings have evolved to see. X-Rays damage the cells, whereas, the IR and UV rays are better identified with heat detectors than visual systems. 

## Making an image
What reaches the eye is the chaotic photon flux, the biological mechanism (eye) creates an ordered image (a usable stimulus form the photons, that doesn't has an image in it, per se.)

![Photon flux and image on the eye](/VPBImages/photonFlux.png/)
 
We have evolved a way of dealing with this "Inverse problem" has determined both how we see and what we see. They are not illusions, it is the way we see the world.

## Organisation of the Human Visual System

## Eye Part 1:
The basic function of the eye is to create an image. An image on the retina which is where the nervous system begins. The retina is actually an outcropping of the nervous system and embryonically part of the brain. 

![](/VPBImages/eye.png)

The generation of the image begins with the cornea. Lens has the function to let the light rays fall on the retina. (Refractive elements)

In the fundus of the eye: (retina)
1. The Optic disk (or papilla): axons/retina exit the eye. 
2. Central Vision: consists of the Macula lutea, which is absent in blood capillaries.  Fovea is contained in the middle of this region. It is most sensitive to detail and has the finest resolution.  
> While observing a scene, the point at which we want to have the greatest observation, it's image falls on the Fovea. 

![](/VPBImages/retina.png)

## Eye Part 2:

![](/VPBImages/eyeTrackExperiment.png)

The above figure illustrates the saccadic (rapid movement of eye between fixation points) movement of the eyes. At these points eyes momentarily stop to gain information.

> Q. In segmented cropped images, we can calculate the density of fixation points. The more denser fixation points are, the rudimentary these features are in the TD Map's incremental model. 

## The Retina Part 1:

![](/VPBImages/retinaCircuit.png)
The foveal region does not contain the ganglion layer and the bipolar cells. The absorption, transmittance and reflectance fraught by the other layers and diminish the sensitivity.

The cells which transduce the light (photoreceptors) are farthest from the light. The reason, the photopigment layer has to be closest to the pigment epithelium due to high metabolism which requires high replenishments. 
The Retina Part 2:
![](/VPBImages/distributionRodCones.png)

Represents the angle of view (the span of the retina) and distribution of rod and cones on each portion of the retina. Fovea is abundant in cones and, the central portion has zero rods. [Central Vision]

The other areas are much more abundant in rods than cones.=

Why do we have cones and rods?
We see a wide range of luminance: from starlight to sunlight. We need to see in the darkest of light to the lightest of light. Although, both rods and cones have the same sensitivity, many rods converge onto a single ganglion. 

The convergence of many rods (about 100, threshold of human vision), makes many rods detect a single photon each. Whereas, for the cones, they are able to capture many photons, onto a single ganglion cells -- increasing the resolution. 

## The Primary Visual Pathway 1:

![](/VPBImages/visaulPathway.png/)

Eye --> Thalamus --> Ocipital Cortex

The primary visual pathway is the key to the perception. Optic Chasm has the function of crossing the scene information on either side of the fovea. Edinger-Westphal nucleus has the responsibility of dilating the pupil to light reflex. Superior colliculus has the function of orienting the movements of the head and the eyes.

### The Primary Visual Pathway 2:
The Lateral Geniculate Nucleus in the Thalamus: it is a way station for many pathways; 

![](/VPBImages/layersThallamus.png/)

The Magno-cellular layers focus on the movement/ change in the image, whereas the parvo cellular layers focus on the colour in the primate vision.

Retinotopy is maintained throughout the visual system. The closely neighboured rods in the retina will map to consecutive lateral-cut layers in the Parvo & Magno-cellular layers. 

> Q: "What if we sedate the Thalamus layer in such a way that the vision is controlled to only seeing brightness levels, rather than colours?" (The answer might be available to those who have studied various animals' Lateral Geniculate Nucleus or the neuroscientists dealing with color-blindness! -HA

Why do we need a way-station, if we can directly send the information to the visual cortex? The information coming into the thalamus and going out is not radically different. The surprising observation here is:

The feedback received from the visual cortex is almost ten times to what is received from the retinal front. What this feedback information is doing is the ongoing mystery?

> "Possible explanation: the feedback lets the Lateral Geniculate Nucleus know the information that it further needs for analysis from the first top-down map.

Just another detail, P ganglion cells and M ganglion cells exist that direct output to the P & M ganglion cell layers.

## Visual Cortex (Part 1):
> A lot of volume is dedicated to looking at **what to look at next?** On the retinotopy perspective, the region of cortex corresponding to the fovea (a very small region on the retina) is ginormous.

![](/VPBImages/radioSugarExp.png)

The radioactive sugar technique was used on the Rhesus monkey to evaluate the retinotopy, where in consecutive circles on a plane were observed as conical pattern on the visual cortex. 

## Visual Cortex (Part 2):
Everything behind the parieto-occipitaq sculls is the occipital cortex. Most of the occipital cortex is the visual cortex, but not all. fMRI was used to identify the regions of V3a, VP, MT. To reveal active regions in the brain in the human brain, uses metabolism as the radioactive experiment. But instead of the sugars, we record the activity of the blood flow. The activity reveals these different areas. 

![](/VPBImages/visualCortex.png)

The image represents the various regions of the visual cortex. V1 is the primary region. To see how the areas are related to each other, we need to get over the peaks and valleys (sulci and gyro), the Computer software blowed up the brain. 

![](/VPBImages/blowedUpBrain.png/)

V1 - Primary, V2 - Secondary, V3 - Tertiary. Functional role of the higher order areas, get the lower level info from V1. What's known about these regions? 
> "INCREMENTAL LEARNING" Shouting out!!! -HA

V4 is biased to cells that respond to colour.
MT, MS are sensitive to change in motion. NOTE: But all of the cells in V4, MT, MS are not dedicated to these functions. 

>**"The retinotopy is degraded in the higher order visual areas.**" Statement: Their receptive field is much bigger, not a part of the image. But the image as a whole. This clearly supports the theory of incremental learning establishing the relationships between the objects: (a) The cells have other work to do (possibly related to establishing relationships) (b) The cells focus on entire image rather than a part of it (possibly the cells are focussed on working on higher order relation than edges) [CNN, got that right!]


## The concept of Receptive Fields:

FACT: Microelectrodes are used to find the activity of a single neuron or a group of neurons. 

For each neuron there is a locus and space that defines the position of the responsiveness of the cells you're recording from. 

"Receptive fields have been mapped for all levels of the visual system from photoreceptors, to retinal ganglion cells, to lateral geniculate nucleus cells, to visual cortex cells, to extra striate cortical cells. Studies based on perception do not give the full picture of the understanding of visual phenomena, so the electrophysiological tools must be used, as the retina, after all, is an outgrowth of the brain." -Wikipedia, Receptive Fields

# **MODULE 2: Observing Colour, Brightness and Darkness**

To perceive through vision, one has to understand lightness and darkness. Though all animals can't see colour, they are well able to observe lightness and darkness.

## Definitions
1. Luminance: An objective measurement of light intensity per unit area (e.g., candela/sq. meter; physical)
2. Lightness: A subjective impression of the intensity of the light reflected from the object surface. (no units: psychophysical)

## Discrepancies between Luminance and Lightness

Receptive field is the area of vision the neuron/ group of neurons respond to. Receptive field have been found to be organized in a center(+), surround(-) fashion. Cell fires more robustly when illumination is at the centre of the field (+). The side effect of this organisation. The figure shows different cells' receptive fields with respect to an edge. A, B, C, D, E  represent these cells/receptive fields. 

![](/VPBImages/responseActivity.png)

But this is now just a traditional explanation.

## More Complex Examples as Counter Evidence

White's illusion works the opposite way than our classic example. The dark surround rectangle appears darker, than the light surround rectangle. Hence, the receptive field organisation theory cannot explain the context illusion.

In cornsweet's edge: The grey to black gradient when removed reveals identical panels.

	Personal Note: This was less instantaneous to be `aware` of as initially I didn't observe the context. Having been talking about these illusions, I have come to know where to look at. So my eyes without any aberration aligns the fovea to the portion to be seen and consequently observes the context and highlights the illusion.

Mach Bands is the area between the dark and the light region. But this transition, contains a lightest line and the darkest dark. The first graph is the physical reality and the follow-up graph is what we see. 

![](/VPBImages/machBands.png)

## An Empirical Explanation based on accumulated experience, Part 1

To recall stimulus on the retina is an entanglement of illumination, reflectance, transmittance. In this lecture we circumvent the inverse problem, given that we have learned the internal world of perceived information and physical world surrounding us.

What's been our experience between the natural images?

You may see the same organisation of luminance only once in the same image, but for experience, an image has to be observed many times. What if we sample each of these observation into millions of small patches, each of which we might have observed a million times. 

	Curious Question: does the shape of the patch we using matter? 
	Answer: Lecturer says it doesn't matter. 

## An Empirical Explanation based on accumulated experience, Part 2

We put the dark and light surrounds on the images: 

![](/VPBImages/lightDarkSurround.png)

Asking, over the course of human history, what has been the frequency of occurrence of luminance values in a dark surround and a light surround? And when you put a patch that's equiluminant, so this T is this patch, and this T is this patch, and these Ts are equal to each other. We put these same luminance patches in a dark surround or a light surround, we see them as different. And this explains why that is. You can see that the same luminance value is going to have a different empirical rank in a dark surround, Than it has in the light surround. So in the light surround, the empirical rank of this center patch is much lower. It's occurred much less often than the same patch in a dark surround. So your experience over the eons of human evolution is that when a patch of this particular luminance is stuck in a dark surround versus the light surround, the rank of your experience has been very different for those two patches. You've much more often seen the same luminance value in a dark surround than that value in a light surround. And the idea is that the explanation of this difference is that the two identical patches in these two contexts, dark and light, occur because the perceived value or subjective value, doesn't track physical movements, it tracks the significance of our perception for behavioral success. We can't see the physical luminance.

## Summary of Module 2.1

Tracking experience aligns lightness percepts on a subjective scale according to their impact on reproductive success.

## MODULE 2.2: Definitions

Color: the set of perception elicited by the spectral distribution of light energy. Previously we have been talking about the quantity of this energy. The basis of color is an extension to this quantification, to a distribution.

Physical Measurement: the relative intensities of wavelengths of light measured with a spectrophotometer.

Psychophysical Measurements: report of the color seen by the subject, typically made by comparison. 

## Light and color
The qualities we call colours are generated by the visual brain. THEY ARE NOT THE PROPERTIES OF THE OBJECTS. Curiously enough, there is NOOOO one to one relationship between the colours seen and the wavelengths. 

## How the Retina Initiates Color Vision (Part 1)
To see color (Distribution of energy), we need more than one receptor type. If we had only one receptor there was no standard of comparing the incoming energy. 

![](/VPBImages/trichromacy.png)

(Short Middle and Long Cones) + Rods

Spectral sesnitivities Graph shown above as developed by George Wald. 

Trichromacy: three different receptors. 

From the central to the peripheral retina, the cones become more and more sparse. This can be proved through the experiment that one you focus over a point in space and try to deduce the color some radians far, it becomes very difficult as the cones become sparse and sparse.

In colorometry, the Long Medium and Short waves are mixed together for the observers to match the color. 

## How the Retina Initiates Color Vision (Part 2)

Color Opponency: Blue and yellow are perceptual opposites. Same with red and green.

NOTE: The receptive cells (in every part - visual cortex, Ganglia cells, retinal cells) have a center surround arrangement. They are excited (+) by light that falls on the center and inhibited (-) by light that falls on the surround.  

We have cells with Red (+) and Green (-)


## Why do we have color vision?

![](/VPBImages/colorVSblack.png)

## Describing Color Perception
Hue: color we see
Saturation: the degree to which hue differs from neutral grey. 
Lightness/Brightness: the intensity of a coloured surface or source. 

![](/VPBImages/perceptualColorSpace.png)

The special thing about each of the disks in the perceptual color space is we have 4 unique categories. People see these categories in their pure form. People mark them to be independent of the add mixture of the other. [NOT YET SOLVED AS TO WHY?] 

## The strange way we see color!
1. The same spectral colors viewed as different colours: Contrast effect.
1. Two spectra of different color viewed as similar perceptually: Constantcy effect. 

![](/VPBImages/contrastVSconstantcy.png)

The context plays an important role too on the color we see.

![](/VPBImages/contextOpponency.png)

## An empirical answer (Part 1)

Color like Luminance also suffers from the deep rooted inverse problem. Each of the illumination, reflectance and transmittance adds its own properties to the spectral distribution of energy. 

ANSWER: SAMPLING COLOR SAMPLES [Sampling color experience]

## An empirical answer (Part 2)

![](/VPBImages/colorBiology.png)

The two central targets look different because of their historically different evolution. 

TOPIC SUMMARY: EVOLUTION, PERCEIVED REPRODUCTIVE SUCCESSIVE, WAY AROUND INVERSE PROBLEM. 

# Module #3 - Seeing Space

## Lesson 1: Geometrical "Illusions"

![Classical Geometrical Illusions](/VPBImages/geoIllusions.png)

As in the previous cases we cannot explain the geometric illusions with the general intuitions that this is the way we have come to see things. 

## Lesson 2, The inverse problem in geometry

![](/VPBImages/geoInverse.png)

How is that we behave appropriately in responding to the geometry of the world?

## Lesson 3, Seeing the lengths of the lines

With different orientations of a horizontal line we see different lengths. 

![](/VPBImages/orientationPerception.png)

## Empirical Explanation

It is done on the basis of experience with those lines. 

![](/VPBImages/experiencePerceptOrientation.png)

Consider, for instance, a projected line 7 pixels in length oriented at 20° (this length corresponds to ~1° of visual angle, a length often used in psychophysical studies). The cumulative distribution of the sources of lines oriented at 20° gives a cumulative probability value of 0.1494 for a line of this length. Thus 14.94% of the physical sources of lines oriented at 20° generated projections equal to or less than 7 pixels in length, and 85.06% generated longer lines. Accordingly, the empirical rank of a line of this projected length oriented at 20° is 14.94%. The empirical ranks of lines 7 pixels in length at different orientations ranging from 0-180° can be similarly determined from the relevant cumulative probability distribution.

In Figure 6 these data are compiled to show how these rankings vary as a function of line orientation for a projected line that subtends a particular distance on the retina. This systematic variation predicts how the perceived length of a line is expected to change as a function of orientation. Comparison of the function in Figure 6 with the psychophysical function in Figure 3B shows how well these predictions can explain this otherwise puzzling aspect of what we see.

![](/VPBImages/cumulativeOrientation.png)

## Lesson 6, Empirical Explanation of Perception and Angles
![](/VPBImages/naturalVShumanAngleFrequency.png)

**Frequency is determined by laser beam scans**

The results provided by these graphs:
1. The frequency of occurrence of right angles is less than the acute and obtuse angles in every case. 

![](/VPBImages/rightVSobliqueReason.png)

The same length of lines as right angles are always going to take up more space, more physical space than the lines, the same length lines as acute or obtuse angles.

You'll recognize that larger planar surfaces in the world, are much less, frequent in occurrence.

## Lesson 7: Seeing Object Size

![](/VPBImages/sizeContrastEffect.png)

## Empirical explanation for seeing the object size different:

### Ebbinghaus Effect (First [A] Size Contrast Effect)
We are creating a template of the central circle with the context of varying size circles. 

We will sample the laser scanned Images millions of times to get a probability distribution of how often we are getting this context in our experience. 

![](/VPBImages/resultsEbbingauhsEffect.png)

## Seeing distance and depth

Distance, refers to the sense of how far away something is, and is mediated **monocularly**.

Depth refers to the special sense of three dimensionality (called stereopsis), and is mediated **binocularly**.

## Seeing distance with one eye



Monocular cues are described under projective geometry further as: 
1. Perspective: The phenomenon that distant things looks smaller than nearby objects. 
2. Aerial perspective: the further the object the more **blue sky** between the observer and the object. 
3. Motion parallax: for a displacement D of an observer. The apparent displacement of the objects is -D<=-d<=0 with objects closer to the observer displacing more than the objects farther from the user. 
4. Specific distance tendency: [Blue->Physical Position], [Red->Perceived Position]

![](/VPBImages/distanceTendency.png)

How do we learn these cues: 

![](/VPBImages/contourElevation.png)

These rather subtle things and show that they are also learned. You can predict what we see on the basis of the frequency or occurrence of images that we experience.

The problem with having one eye is that you can't see beyond your nose. 

## Seeing depth with Two Eyes (Stereopsis):

Charles Wheatsone has seminal contribution in explaining why two eyes bring a sense of depth. When we see the world, with our eyes 65 mm apart we get two images. 

![](/VPBImages/depthWheatsone.png)

We have different perception with each eye. He invented the stereoscope. On two opposite image of a stereoscope reel are pictures of the same object taken from cameras (which are more than 65mm apart) from left and right positions creating a sense of depth. 

Perform the pen experiment.

Wheatstone switched what we would normally expected to see? Through a pseudo scope. 

BAS RELIEF AND INTAGLIO

And of course when they look at distant objects, the stereoscopic effect goes down and you have to see it with bigger and bigger objects because the eyes are more and more parallel. And that should be obvious looking at a diagram such as the ones that we use to show that the two eye views are different, like this. This is remember our greeting distance, 30 centimeters so as you go further and further distant in the objects that you are looking at they have to be bigger and bigger separated by bigger and bigger distances in real world space to generate some sensations during a scalpic depth at a distance.

![](/VPBImages/pointMatching.png)

Points on the horopter (all the points equidistant in depth from the observer) at the plane of convergence formed by the fovea.

The points not on the horopter are projected away from the fovea on the retina. We have to match points p and q. Unsolved problem on how brain does that [Correspondence Problem]. 

Neural Activity in response to objects at varying distances causes excitation at different stimulus points. 

![](/VPBImages/nearFarActivations.png)
 
## Random Dot Stereograms and the Correspondence Problem

RD Stereograms were developed by Bela Julesz to explain stereoscopic vision. 

![](/VPBImages/rdStereograms.png)

To break the camouflage one has to use stereoscopic vision. 

What's the message of the stereoscopic vision to correspondence problem?

Image matching

RDStereograms bring out the capability of matching random dots to form an image. 

**THE SCIENTISTS ARE NOT CLEAR HOW IT'S DONE**

## Lesson 6 Binocular Fusion

How are the two images put together?

![](/VPBImages/binocularFusion.png)

Where do the two eyes' information come together?

The layer four of neocortex. Kept in columns separately. They come together in the layers above and below that. There are cells that respond to monocular vision and others that respond to the binocular vision. 

![BINOCULAR RIVALRY](/VPBImages/binocularPercept.png)

![](/VPBImages/sherringtonExperiment.png)

Flicker Fusion Rate: There is a frequency at which, when the light flickers, it appears to be stabilised -- called the flicker fusion rate. 

To find if there exists a final comma pathway between the two eye inputs?

Flashes of light are given to the eyes independently synchronously and asynchronously. 

The synchronous flashes are half the frequency of the asynchronous flashes where they come alternatively to the left and right eye.

Flicker fusion rate was same in both the sync and async patterns. 

**SCIENTISTS DON'T KNOW HOW FUSION OF TWO IMAGES COME TOGETHER**

# SEEING MOTION

## Definitions

1. Translation and/or rotation in Euclidean (3D) Space
2. Physical speed and perceived speed.
3. Physical Direction versus perceived direction

Direction and speed define motion in 3D space [Physical] and 2D Space [Perceived].

## Some Phenomenons

1. Apparent Motion [Time]: The subjective generation of sense of smooth motion from images that are sequentially static. How sequential images on the retina appear to be a smooth series? If the frequency of flashes is above a certain frequency, the movement appears to be smooth.
2. Motion After Effects [Tiring]: If you look at an object for a long enough time. Eg. Waterfall After Effect. Stare at pouring water for 30s, the walls will start moving downwards. The neurons that get activated with the red square and by the downward motion of the waterfall get tired after the staring activity. The neurons which are activated by green or by upward motion are relatively more active and hence their activity causes the motion after effect.


## The inverse problem of motion: 

The effects discussed above fall into a different domain than the inverse problem, hence discussed separately. 
![](/VPBImages/motionInverse.png)

If these differently oriented and differently sized objects are projecting the same image on the retinal plane as they traverse, how does the observer know the objects to be different?

3. Perceived speed and The flash-lag Effect: We are going to discuss the disconnect between the percept speed and the physical speed. The phenomenon of the flash lag effect elicits it:  

	![](/VPBImages/flashLagEffect.png)
	
	When the flash of light occurs it seemed not in the same position with the red bar. The flash lags the red bar. With a faster speed of the red bar the lag increases. 

	The idea is really a very simple one, it's just a way of measuring the amount of lag that an observer sees as a function of the speed of motion of the red bar moving across the screen.

	![Test Setup: Flash Lag Effect](/VPBImages/testFlashLagEffect.png)
 
	![Results: Flash Lag Effect](/VPBImages/resultsFlashLagEffect.png)

	The results can be explained through the explanation below:
	
	There is currently no apparatus that can capture the frequency of occurrence of the speeds of moving objects projected onto the retina. 
		
	We consider an artificial visual space wherein the particles are moving in different direction all with the same speed. All of these particles are projected onto the retina. The particles moving away or close to the frontal plane rather than onto the frontal plane have a projected velocity lower than their actual physical speed. Since the probability of occurrence of the particles in any direction is same, the probability of frequency of occurrence is higher for lower values of speed.
	
	![](/VPBImages/probabilityFoO.png)
	
	![](/VPBImages/empericalVSperceivedLag.png)
	
	We take the cumulative ranks an plot it with the results of the flash lag experiment. The cumulative experience of the frequency of occurrence of speeds explains the flash lag effects with the linear plot. 

4. Perceived Direction: Aperture Effects, 
	An aperture is the limited space through which you see something. How to explain the aperture effect i.e how this context that causes a different perceived motion than the physical motion.
	
	**Step 1: Determine the directions people see when a given aperture is applied**
	In the circular aperture, the observers reported the line to be moving in a direction that is orthogonal to the orientation of the line. 
	
	**Step 2: Collect the relevant  empirical data about lines projecting on the retina through the aperture.**
	Make a simulate 3D Visual space, populate the space with rods, moving through the space with different speeds and different directions. Add a circular aperture to the view on the 2D plane. What is the human experience with projected directions through the aperture? 
	
	![](/VPBImages/apertureExperience.png)
	
	The jagged squiggles show the probability distribution of the occurrence of orientation in that direction.
	
	**Step 3: Compare the Psychophysical results with the frequency of directions experienced.** The mode of the probability distribution of the projected directions closely accords with the perceived direction. 
	
	The bias in the Prob Distribution arises because lines moving orthogonally to their orientation will satisfy the aperture more often than lines moving in any other direction. Thus the prevalent  projected direction of lines moving in a circular aperture; this is what humans will have always experienced.
	
	![](/VPBImages/PDBias.png)
	
	The first one satisfies the aperture with a shorter line length (orientation is perpendicular to the motion). In other words, it is able to satisfy the aperture with the minimum possible length of lines by moving in an orthogonal direction.
	
	As shorter lines are always part of longer lines, the mode will always be towards the orthogonal direction. 
	
	# Module #5
	## Alternative Conceptions of Vision
	
	It is not necessary for these conceptions to be mutually exclusive to each other. 
	
	1. Feature Detection: Hubel and Wiesel described a great case for vision as feature detection.   
		![](/VPBImages/catHubelWiesel.png)
		A cat's inheritance has defined, just like a human being - a receptive field of individual neurons. In the example here, there are bars of light that are oriented in one orientation or another. And recording from an individual cell, cell by cell with a microelectrode which doesn't go inside the cells but is an extracellular microelectrode that records when you place it in the cortex, the primary visual cortex, in this case, of the cat, records from one cell or another. point is that there's a location in visual space that any particular cell is going to respond to. There is a list of characteristics that a cell 'LIKES'. The Hubel and Wiesel experiment tested the orientation characteristic. In this way we can define a tuning curve for each cell for different charactristics. How does this imply that neural activity represents image features: that's a feature that the cell responds to and there's a particular orientation that it likes. So one would imagine from that that vision is all about detecting features, measuring the features in the world, reporting them to the sensorium, to our visual brains, by virtue of the features that are on the retina that are translated into features in our perceptual sense, and that those features correspond in some way to reality. Visual perception, the end product of vision, was not talked much in their book 'Brain and visual perception'. The lecturer believes that perception would fall out of the anatomical structure of the neurons, they didn't think that it would have a psychological effect. The problem with feature detection: Image features do not measure objects in the world. There's a many-to-one problem.
		![](/VPBImages/geoInverse.png)
		
	2. Vision as inference: Hermann von Helmholtz knew that the visual system was not a very good optical system. It was not as good as the lenses in his ophthalmoscope and he was aware that the image on the retina is actually a fairly crummy representation as images go. He mentioned that this optical system required a subjective system to INFER the meaning (UNCONSCIOUS INFERENCE) drawn from experience. This subjective system improves or takes into account what our physical system cannot take. Today, when we talk about inference we talk about the Bayesian inference. For P (A | B) = (B|A) * P(A), A is an image and B is the underlying state of the physical world. The Baye's Theorem is only marginally helpful in the problem of vision. The B term in Baye's theorem is not available due to the inverse problem.
	3. Vision as efficient coding: Shannon developed the information theory by inventing compression of messages in telecommunications through an information processing system. The visual brain is an information processing system. The logic of efficient coding in neuroscience is that the neurons use action potentials to communicate with other parts of the body. A signal (in milliseconds) is generated by the neuron and decoded at the destinations. Horace Barlow noticed that the concepts of information theory can reduce the redundancy in the images observed by the visual system. The problem in this case is that the machoism of transmission are not those of perception. The message and its transmission are two different things.   
	4. Vision as a way of contending with the inverse problem. 

# What Vision implies about How Brain Works

## Does the brain work by computing?
## Or is Braine an Engine of Reflex Associations

A reflex is an automatic response that's simple straightforward ands always the same. 