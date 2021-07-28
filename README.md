# Call for Code solution starter kit: Clean water and sanitation

[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Community](https://img.shields.io/badge/Join-Community-blue.svg)](https://developer.ibm.com/callforcode/get-started/) [![Website](https://img.shields.io/badge/View-Website-blue)](https://developer.ibm.com/callforcode/get-started/climate-change/clean-water)

The need for clean water is not only limited to humans but also extends to all living things as a naturally occurring component for life continuity on planet Earth. Water quality monitoring is important for guiding safety management and ensuring public health. With a global estimate of 7 billion dreams, many of whom still lack access to quality drinking water, it’s important to share knowledge and information all around the world to break the vicious cycle of ignorance and water wastage. With expatriate estimates of water project costs, this shall reduce failure of building water safety capacity.

## Contents

1. [Short description](#short-description)
1. [Video](#video)
1. [The architecture](#the-architecture)
1. [Getting started](#getting-started)
1. [Contributing](#contributing)
1. [Acknowledgments](#acknowledgments)

## Short description

This starter kit can help you begin your Call for Code solution. The starter kit pulls together resources to help you and your team use technology to create applications to tackle clean water and sanitation issues around the world.

### What's the problem?

According to the [World Health Organization](https://www.who.int/news/item/18-06-2019-1-in-3-people-globally-do-not-have-access-to-safe-drinking-water-unicef-who), 2.2 billion people around the world do not have safely managed drinking water services, 4.2 billion people do not have safely managed sanitation services, and 3 billion people lack basic handwashing facilities. These services are critical in preventing the spread of COVID-19 and other diseases. Even in areas that have these services, there are vast inequalities in the accessibility, availability, and quality of the services. 

UNICEF is urgently appealing for funding and support to reach more children with basic water, sanitation, and hygiene facilities, especially those children who are cut off from safe water because they live in remote areas, in places where water is untreated or polluted, or because they are without a home, living in a slum or on the street.

### How can technology help?

From intelligent solutions for small farmers to recycling showers, technology can make a significant impact on the availability of water and its consumption. IBM provides various technologies such as IoT, Watson, and blockchain. [IBM Water Management as a Service platform](https://www.ibm.com/thought-leadership/water/) can monitor water resources in real time. Through this cloud-based platform, IBM is helping to improve the management of water resources.

Additional ways Water Management as a Service can help:

- Creating a database and [interactive map](https://wmaasp.mybluemix.net/sensor-overview) to help locate and maintain the water points across the counties
- Collecting water usage, breakage, and repair data from boreholes that are monitored by SweetSense
- Delivering tickets to repair and maintenance teams who can respond to failures and repair the boreholes

### The idea

To encourage optimal water choices by consumers and local governments and to incentivize water sustainability, we propose devising and implementing an API for water data collection and dissemination. With an API, you could have a centralized way to:

- Query geolocations of sustainable water sources
- Simplify coordination and funding for water construction projects
- Explore educational tools to support water sustainability and clean water access
- Enable transparent water usage, cleanliness results, and site-to-site comparison
- Access plain language case studies and legislation

### Solution ideas

This section provides several examples that you and your team can use to jump-start your solution ideas. The following ideas are examples only, so feel free to brainstorm with your team to create your own original ideas and solutions. For example, the 2020 Call for Code Grand Prize winner, [Agrolly](https://developer.ibm.com/blogs/agrolly/) created a solution that uses IBM Cloud Object Storage, IBM Watson Studio, IBM Watson Assistant, and The Weather Company technologies to execute climate risk assessments, which allows farmers with less resources available to them to still make more educated decisions, obtain the necessary financing, and improve their economic outcome.

In the following examples:

#### Idea 

![A community leader can find verified clean sources of water near to them in one place in near real time 
and track/compare water sanitation results against historical trends + nearby communities to drive a ~50% reduction in water illness-related hospitalizations
and can assess their water usage and make more informed decisions to prioritize most essential needs & decrease water waste.]

Essential technologies needed:

- Water analysis technology (IoT)
- GPS location data for water sources relative to user location
- Maps of surface water, aquifers, rainfall, and watersheds relating to user location
- Historic data on local rainfall
- Historic comparison of color of surface water over time from satellite imagery
- Rainfall forecast
- Lab test results of water quality upstream and downstream
- Water flow rate sensors to monitor household irrigation
- Track and trace
- Publicity of results and water source to report mapping
- Pollution source remediation and containment

## Video

[![Watch the video](https://img.youtube.com/vi/e6gdcsNZN-Q/0.jpg)](https://www.youtube.com/watch?v=e6gdcsNZN-Q)

## The architecture

![Starter kit architecture diagram](assets/CFC-CleanWater-Architecture.png)

1. The user or community leader accesses a Clean Water Insights Dashboard.
1. The insights dashboard requests the Clean Water API for data that the user wants (including queries made on a chatbot).
1. The user can converse with a chatbot to get necessary information, and the insights dashboard can act as an orchestration application for the chatbot.
1. The Clean Water API component retrieves the required data from various sources and aggregates them as necessary.
1. A machine learning module uses the data sources as a corpus to build a recommendation model and hosts that model.
1. The Clean Water Water Insights Dashboard can get recommendation and prediction information from a recommendation engine.

## Getting started

You can create a solution based on the proposed solution architecture by exploring the following resources on [IBM Developer](https://developer.ibm.com/).


## Contributing

Please read about [contributing](CONTRIBUTING.md) to this repository for details on our code of conduct and the process for submitting pull requests.

## Contributors

- [Dr. David O’Hara](https://www.linkedin.com/in/david-o-hara/), Chair and Professor of Philosophy and Environmental Studies, and Director of Sustainability and Environmental Studies, Augustana University
- [Dr. Mark L. Meiklejohn](https://www.linkedin.com/in/markmeiklejohn/), Senior Software Engineer, JP Morgan (Suisse)
- [Karla Readshaw](https://www.linkedin.com/in/karlareadshaw/), Program Manager, Education at Intuit  
- [Romeo Kienzler](https://developer.ibm.com/profiles/romeo.kienzler/), IBM Developer Advocate, Data science 
- [Muralidhar Chavan](https://developer.ibm.com/profiles/muralidhar.chavan/), IBM Developer Advocate, Artificial Intelligence 
- [Mateo Bozzini](https://developer.ibm.com/profiles/mbozzini/), IBM Developer Advocate, Platform Development
- [John Walicki](https://developer.ibm.com/profiles/walicki/), IBM Developer Advocate, IoT and Edge
- [Niraj Swami](https://www.linkedin.com/in/nirajswami/), Conservation Technology Strategy & Enablement, The Nature Conservancy
- [Christoph Gorder](https://www.linkedin.com/in/christoph-gorder-0745a2/), Chief Global Water Officer, charity: water


<a href="https://github.com/Call-for-Code/Solution-Starter-Kit-Water-2021/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=Call-for-Code/Solution-Starter-Kit-Water-2021" />
</a>

## License

This starter kit is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details

- [Charity Water](https://www.charitywater.org/global-water-crisis)
- [Nature Conservancy](https://www.nature.org/en-us/what-we-do/our-priorities/provide-food-and-water-sustainably/)
