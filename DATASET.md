# Dataset Descriptions

This repository contains descriptions of three datasets used in analyzing member engagement, event participation, and trends for the Pittsburgh Technology Council.
* The datasets used in this project are proprietary and were provided by the Pittsburgh Technology Council. Due to the sensitive nature of the data, the datasets are not included in this repository. However, detailed descriptions of the datasets are provided below to offer insight into their structure and variables, enabling others to replicate similar analyses with their own data.

## 1. Scorecard Dataset

### Overview
The Scorecard Dataset contains information about scorecards created for member companies. It helps analyze member engagement, scorecard usage, and related trends.

### Columns
1. **Company**: Names of the companies associated with the scorecards.  
2. **SC Date**: The date the scorecard was created.  
3. **SC Entry Date**: The date the scorecard was recorded in the system.  
4. **SC Type**: The type of scorecard (e.g., General: Outreach (in person), Visibility: Event Listed on Web Calendar, Business Development: Introduced to Prospective Customer (in person), Talent: Participated in a Job Fair, Fortyx80: STEM Engagement Corporation, Advocacy: Government Procurement Assistance... ) 
5. **Value**: A binary column indicating whether the scorecard holds value for analysis (0 or 1).  
6. **Expected Rate**: A numeric column representing expected rates, ranging from 0 to 10,000.  
7. **SC Owner**: The name of the person responsible for the scorecard.  
8. **Paid Through Date**: The deadline for the company to pay its membership renewal fee.  
9. **Member Type**: Membership status of the company:  
   - **NM**: Not a current member.  
   - **M**: Current member.  
   - **MN**: New member.  
10. **Category**: The category of the company:  
    - **TECH**: Technology.  
    - **ENT**: Entrepreneur.  
    - **NP**: Non-Profit.  
    - **TU**: Technology User.  
    - **EDU**: Education.  
11. **SC Note**: A blank column with no values.  
12. **ScorecardEmail**: The contact email of the company representative or the value "X" if unavailable.  
13. **SC Description**: A brief description or notes about the scorecard.  

### Notes
- The **SC Type** column is central to understanding member interactions.  
- **SC Note** is a placeholder column and does not contain meaningful data.  
- **ScorecardEmail** provides a contact point, but "X" indicates missing data.

---

## 2. Event Attendees (2018-2023)

### Overview
This dataset includes information on individuals and companies who attended events organized by the Pittsburgh Technology Council from 2018 to 2023.

### Columns
1. **First Name**: The attendee's first name.  
2. **Last Name**: The attendee's last name.  
3. **Company**: The name of the company the attendee represents.  
4. **Registrant Email**: The email address of the attendee.  
5. **Register Type**: The type of registration for the event:  
    - Sponsor Attendee  
    - Table Attendee  
    - Event Sponsor  
    - Other registration categories.  
6. **Title**: The title or name of the event the attendee participated in.  
7. **Event Code**: A unique identifier for the event.  
8. **Member Type**: Membership status of the attendee’s company:  
    - **NM**: Not a current member.  
    - **M**: Current member.  
    - **MN**: New member.  
9. **Paid Through**: The date until which the company’s membership is valid.  
10. **Join Date**: The date the company became a member.  

### Notes
- The **Register Type** column identifies the attendee's role or purpose in the event.  
- **Event Code** enables event-level analysis.  
- **Member Type**, **Paid Through**, and **Join Date** link event participation to membership trends.

---

## 3. EventBrite Attendance Companies Dataset

### Overview
This dataset contains information about ticket purchases and buyer details for events organized by the Pittsburgh Technology Council.

### Columns
1. **Order ID**: A unique identifier for each ticket order.  
2. **Order Date**: The date the ticket order was placed.  
3. **Attendee Status**: The status of the attendee (e.g., registered, canceled).  
4. **First Name**: The attendee's first name.  
5. **Last Name**: The attendee's last name.  
6. **Email**: The attendee's email address.  
7. **Event Name**: The title or name of the event associated with the order.  
8. **Ticket Quantity**: The number of tickets purchased in the order.  
9. **Ticket Type**: The type of ticket purchased:  
    - General Admission  
    - Standard Ticket  
    - Finalist Ticket  
    - Other ticket categories.  
10. **Ticket Price**: The price of a single ticket.  
11. **Buyer First Name**: The first name of the ticket purchaser.  
12. **Buyer Last Name**: The last name of the ticket purchaser.  
13. **Buyer Email**: The email address of the ticket purchaser.  
14. **Company**: The name of the company associated with the ticket buyer or attendee.  
15. **Additional Notes**: Supplementary information related to the ticket order or attendee.

### Notes
- The **Ticket Type** column categorizes ticket preferences.  
- **Order Date** and **Event Name** help analyze sales trends.  
- Buyer-related columns distinguish between the attendee and purchaser.

## 4.BenefitParticipants Dataset

### Overview
This dataset provides information about companies participating in benefit-related activities, focusing on their membership status. The dataset contains the following columns:

1. **Company Name**: The name of the company participating in the activity.
2. **Member Type**: The membership status of the company, categorized as:
   - **NM**: Not a current member.
   - **M**: Current member.
   - **MN**: New member.

### Notes:
- This dataset is useful for analyzing the distribution of membership types among benefit participants and understanding how these activities may correlate with member retention or engagement.
