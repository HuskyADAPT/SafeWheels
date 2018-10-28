![Go Baby Go Seattle](https://www.marymount.edu/getattachment/Academics/Malek-School-of-Health-Professions/Graduate-Programs/Physical-Therapy-(D-P-T-)/Go-Baby-Go-at-Marymount-University/go_baby_go_logo.jpg.aspx?width=400&height=352)

# Need Statement
Children need more accessible steering options for ride-on cars, which enables movement because every child deserves to move autonomously. 

# Go Baby Go
After a lab meeting in a local toy store led by founder Dr. Cole Galloway, Go Baby Go began in 2012 as a grassroots program to fulfill a need for an affordable, socially inviting, and customizable early powered mobility option for young children with disabilities, through making simple safety and accessibility modifications to commercially available, battery-powered toy ride-on cars. It is now an international movement, with Go Baby Go team members conducting mobility and developmental research, running car modification instructional workshops for families, therapists, and community volunteers, and advocating for the recognition of self-directed mobility as a basic human right. You can learn more by visiting the Go Baby Go website, and our Seattle Go Baby Go Facebook page.

Go Baby Go cars provide a fun and inviting way for young children with and without disabilities to move around, play with their peers, and explore their environment. Usually, the child activates the car by pressing a large, easy to press button, positioned on top of the steering wheel. In many cases, however, steering the car on his or her own is difficult for the child, due to differences in hand and arm coordination, range of motion, and/or strength. Caregivers, siblings, or therapists often have to turn the steering wheel for the child, and to do this requires bending over a moving vehicle, which is uncomfortable to do for long periods of time, and decreases the independence that can be enjoyed by the child. This design challenge involves creating child-led steering solutions for a Frozen™ Go Baby Go modified ride-on car, so a child may activate and steer the ride-on car independently, regardless of upper extremity ability. These solutions should be safe, affordable, replicable for other car models and other children, and allow for improved access of both child and caregiver to enjoy their Go Baby Go car.

# Challenge

Since toddlers are so young, very few powered wheelchairs exist to accommodate motor disabilities, and options that do exist are usually too expensive, and too impractical with respect to user development. The high costs, complicated mechanics, and intimidating stature of existing motorized wheelchairs conflict with the nature of toddlers, who need to be motivated to explore and interact with their surroundings. 

Go Baby Go addresses this discrepancy in disability service by modifying toy ride-on cars to make them more accessible and ergonomic. The customizable control schemes, low seating height, and fun aesthetic designs promote the user to interact with their environment and others, and for others to do the same. Research strongly supports the notion that self-directed exploration, and socialization, significantly benefit the development of a child’s cognitive, communication, social, and motor skills. The promotion of these skills, in addition to the much lower cost of purchasing and modifying a toy car, makes Go Baby Go and exciting and potent.

Our involvement in Go Baby Go has been delegated to one pressing challenge that often inhibits complete accommodation of impairment: steering. Motor impairments often introduce difficulty in steering toy ride-on cars, because steering these car requires the toddler to exhibit a considerable amount of strength, dexterity, and intuition with the control interface(a steering wheel, by default). Therefore, our primary goal is to reduce, as much as possible, the factorization of strength and dexterity into operating the car. Reducing requirements for both of these parameters is quite difficult, as many alternate control scheme than mechanical steering require increased dexterity, such as buttons. Ultimately, a compromise had to be made, and so we selected a joystick to be our final steering interface, as it requires little strength, and a reasonable amount of dexterity. 

# Design Ideas
## Joystick
Selecting a joystick as the complete control interface for the driver of the ride-on car means that any mechanical work performed by the car must originate from electrical power. However, the steering of a standard toy car is done through mechanical torsion applied by the driver to the steering wheel. Therefore, the joystick must be configured to deliver an appropriate electrical signal to both the main drive motor, and a power steering motor. This joystick, in order to be ergonomic for children, must have a large dead zone, and responsive output. Getting a potentiometer-based joystick to deliver this power at the right position usually requires digital signal conversion and a computer. To obviate the need for a computer or microcontroller, such as an Arduino, we tried to design an analog circuit that would create a dead zone for the joystick, as well as maximize output beyond this dead zone. After presenting our circuit diagram to our peers, containing four comparators, among other components, we gathered the impression that if it intimidated them, it would intimidate workshop volunteers at GoBabyGo. Under this disappointment, we figured out that it would be much easier to create a joystick that behave the way we want than an electronic circuit. Thus, we switched from using a potentiometer-based joystick to a contact-based joystick, where one must push in a certain direction under conductors come into contact.  

## Steering
We want to use the parts which can be bought easily and do not need professional machine work. The whole steering mechanism is easy to understand by the people even without basic engineering skills. Hence, we plan to fabricate these mechanical parts with 3D printer using ABS material, which is tough and non-toxic. The builders can just receive the electronic-format models and put them in the 3D printer. However, whether the conventional mechanical way should be replaced with the 3D printing method depends on the feedback.  

# Functions
- Accessible controls for child (electronic, responsive, adjustable)  
- Safety of operation (secure seating, no jerky movement, emergency stop switch)  
- User-friendly  
- Ease of assembly (low component number)  
- Affordable

# Progress
17th October 2017: Went to toy store and examined the toy car we will be modifying.  
24th October 2017: Research and ideation of different steering mechanisms using arduinos through online projects.  
31st October 2017: Researched electrical and mechanical possibilities of joystick.  
7th November 2017: Mid-quarter presentation.  
14th November 2017: Researched power steering.  
21st November 2017: Finalised core functions, design idea.  
14th December 2017: Final presentation.
7th January - 16 March 2018: Developed prototype. 
23rd March 2018: Presented prototype at design showcase. 
4th April 2018: Provided resources for future teams to augment prototype.

# Acknowledgements
Dr. Heather Feldner, Dr. Kat Steele, Dr. Shawn Israel, Ms. Brianna Goodwin  
We thank the Mathers Fund to Empower and Improve Human Ability for their ongoing support of HuskyAdapt.

# Authors
Hongjian Jiang , Colin Eckhoff, Kush Tekriwal
