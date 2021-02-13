# LeARning Reimagined 


In response to the COVID-19 pandemic, nearly 6 million public school children transitioned to virtual learning. Many schools, parents, and teachers were unprepared to handle the challenges of distance learning from declining student engagement, zoom fatigue, and decreased learning quality. LeARning Reimagined is here to reimagine distance learning by promoting in-depth, comprehensive science education from the comfort of your home by harnessing the power of AR/VR to bring topics to life! 

Currently, AR/VR products for educational learning rely on buying products to scan an AR code to see models or are placed behind expensive paywalls or services. In a crisis that has impacted students and their families emotionally, financially, and mentally, we created an accessible tool that allows students to explore and learn about science topics in a fun, interactive way. As a free product, this application is easily deployed to smartphones for use and contains an easy to navigate interface with large buttons to address the needs of younger children. Furthermore, we are not only promoting the learning of science concepts but also promote wellness through interactive topics on meditation through breathing exercises, fitness, and wellness. <img align="left" src="images/LeARning Reimagined.png">

Topic Areas:
* COVID-19: Spike Proteins, Healthy Lungs,  Lungs with COVID
* Human Body: Skeletal System, Digestive System, Respiratory System, Eyeball, and Heart
* Wellness: Dog, Cat, Arachnophobia

# How to Use 

You will need an iPhone, iPad, or a Safari browser to successfully use this application. To start using the application, navigate to the LeARning Imagined website (https://learning-reimagined.netlify.app/). From there, click on the subject tab and navigate to the topic of your choosing. Each topic contains a description of the subject area and a basic overview of the concepts you will learn about. When you find your topic area of interest, click on the "Bring to Life" button and watch your studying come to life! Interact with the models by pinching or expanding your fingers to enlarge or minimize the model, rotate it around, and move it around in your space.  


# What we hope to accomplish 

As educators and students continue to navigate the challenges surrounding this pandemic and the difficulties of distance learning, we hope to create an interactive tool that will keep students engaged with their learning and ensure that they do not fall behind. Additionally, science classes rely heavily on the usage of models to learn about important concepts like the cardiovascular system. Instead of placing the burden on students to buy expensive models, we have developed a free, accessible tool that allows students to engage with models that will promote their understanding of human anatomy and other biological concepts. More importantly, the mental crises that have accompanied this pandemic have permeated across all age-groups. Our kids are struggling and we want to help alleviate the burden by providing accessible, and informative avenues to learn about meditation, fitness, and wellness. 

# Obstacles encountered during the project 

On the front end side, the challenges encountered were mostly related to mobile responsiveness. Due to relatively new experience working with the Tailwind CSS framework we had to solve challenges related to finding the appropriate breakpoints for mobile device compatibility. We overcame these challenges by looking at the documentation and understanding the fundamentals of how Tailwind CSS aligns its objects and its grid structure.

Finding the appropriate AR models also proved to be a challenge. Because our application is based in iOS, our final AR files had to be in the Apple/Pixar curated .usdz format. However, a large majority of the 3D modeling files that are out on the internet come in .obj or .gitl formats. After some digging, we discovered that Apple's latest Big Sur operating system came built with an application known as Reality Converter, which addresses our exact problem. It converts all types of modeling files into the Apple native .usdz format.

However, our problems didn't end there. Although essentially every 3D model on the internet was now fair game, many were locked behind a paywall. The free versions were often low in quality, finicky, or simply non functional. This was especially true when it came to the animated 3D models, such as a moving spider or a flapping bird. Almost all animated models cost money. Thus, we were forced to strike a balance between time and quality, erring more to the side of quality. While the website was being designed, my (Pavan) job was to scour the internet for high quality AR models that would deliver the best experience for users. EchoAR was very useful in this instance, because it came preloaded with several great models that were easily integrated into our project. We even discovered that echoAR actually handled the usdz conversion problem as well, and also made for loose coupling modularity by using echoAR links in our code. This way, if we used say the same usdz file in 40 different places within our program and we later had to change that usdz file, we can make a singular change in echoAR and it will be reflected every where it is used.

# Future Initiatives/ Areas of Improvement 

To expand upon the progress made with this project, we hope to leverage the use of platforms like echoAR to deploy interactive models that allow students to drag and drop labels in real-time onto models. We also hope to add other functionality that will allow students to click on the model and see pop-up labels that indicate the specific label of the body part. Finally, our application is currently compatible with Safari browsers and Apple products. In the future, we hope to expand compatibility to android phones and other types of browsers. 

In addition, we hope to improve the AR models that are used. Whether it be developing our own proprietary versions, or finding some of the nicer premium versions, incorporating them over time as the usdz market grows will help to elevate the user experience of our application.
