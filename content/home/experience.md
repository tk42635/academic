+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "10px", "0"]
  
[[experience]]
  title = "Software Engineer Intern"
  company = "Semio"
  company_url = "https://semio.ai/"
  location = "Los Angeles"
  date_start = "2020-05-01"
  date_end = "2020-08-21"
  description = """
  Responsibilities include:
  
  * Built a multi-layer ROS map with regions and waypoints visualized in Arora based on TypeScript and React.  
  * Tracked and visualized body part motion trajectory in decaying pattern with Dynamic-Reconfiguration in ROS.  
  * Processed THÖR dataset to display multiple moving persons’ 3D point cloud and head orientation in real time.  
  * Reproduced part work of [*Bayesian Estimator for Partial Trajectory Alignment*](http://www.roboticsproceedings.org/rss15/p80.pdf) to train a model for behavior recognition.  

  """

[[experience]]
  title = "Software Engineer Intern"
  company = "National Laboratory of Pattern Recognition, CASIA"
  company_url = "http://www.nlpr.ia.ac.cn/en/"
  location = "Beijing"
  date_start = "2019-03-20"
  date_end = "2019-07-01"
  description = """
  Responsibilities include:
  
  * Implemented C++ inference process of neural networks and improved code efficiency by 40% through [Mobile AI Compute Engine](https://github.com/XiaoMi/mace).  
  * Deployed neural networks on mobile ARM platforms such as RK3399, Raspberry Pi and other SoCs.
  * Developed a multi-thread fast video stabilization algorithm based on Kalman Filter and Gaussian Filter (Avg FPS: 149).  
 	* Contrasted multiple human face detection algorithms’ performance (Dlib, libfacedetection, Arcsoft SDK, etc.) on ARMs.  


  """
  
[[experience]]
  title = "Research Assistant"
  company = "Institute of Automation and Control, Beihang University"
  company_url = "http://asee.buaa.edu.cn/"
  location = "Beijing"
  date_start = "2019-03-20"
  date_end = "2019-07-01"
  description = """
  Responsibilities include:
  
  * Researched on omni-directional copters to decouple the relation between multi-copters’ posture and movement.  
  * Proposed collectively a novel flight control algorithm based on quarternion theory and 8 spatial vectors.  
  *	Produced an indoor Octocopter with cubic carbon fiber frame and 8 aerial brushless motors capable of reverse rotation.  
  * Achieved highly-precise indoor localization and long-time spot hovering without floating by using [Pozyx](https://www.pozyx.io/) platform.  

  """
+++
