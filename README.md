# script_sketcher

Website Link : https://script-sketcher.onrender.com/

#### Desktop view -
![image](https://github.com/adarsh2350/script_sketcher/assets/76907802/f9a80931-bcf6-4915-8a6c-cfac60a8cdd5)
#### Tablet view -
![image](https://github.com/adarsh2350/script_sketcher/assets/76907802/b5f184f1-0249-49e2-9978-e019cdcede26)
### Mobile view -
![image](https://github.com/adarsh2350/script_sketcher/assets/76907802/2d0181b9-f525-4bc1-a950-3a83639c56a2)

### Sample Outputs -
![image](https://github.com/adarsh2350/script_sketcher/assets/76907802/54504e91-612e-4c1c-a44a-c152ce30c9c0)
![image](https://github.com/adarsh2350/script_sketcher/assets/76907802/cc5bde8d-0256-487e-923d-cc1fff22ce9f)
![image](https://github.com/adarsh2350/script_sketcher/assets/76907802/8343bdca-042d-4727-8dc2-9aaa2984f5f6)


### Installation

Clone the Repository:
- git clone https://github.com/adarsh2350/script_sketcher_3.git
  
Navigate to the Project Directory:
- cd script_sketcher_3
  
Install Dependencies:
- npm install
  
Start the Development Server:
- npm start


### Objective
The goal of this project is to develop a straightforward web application enabling users to create and share a 10-panel comic strip. Users input text into a form, which is then processed by a text-to-image API, generating the comic panels.

### Features and Technicalities
Frontend:
- Used React for the user interface and interactivity.
- Utilized fetch for API calls from the frontend to the text-to-image API to handle responses (success or error) and update the UI accordingly.

Responsive Design:
- Ensured the application's adaptability across various devices using responsive design principles.

Bonus Feature Implemented:
- Incorporate additional feature of speech bubbles or text annotations using by editing prompt created for API call.

Deployment:
- Deployed the application by using [onrender](https://render.com/), ensuring stability and scalability.

Notes -
- Must have to fill atleast one panel (Panel 1) before generating images otherwise alert will be poped out.
- Not necessary to fill all the fields before generating images (fill as per your requirements (1-10)).
- Speech bubbles not necessary to fill, can fill only some of them as per requirement. 
