# ML_CFPB_Complaint_Classification
<b>Group Members : Anirudh Bhamidipati, kanha Baidya, Yashesh Darji and Bonyshree Bose</b>

![CFPB](images/Report-to-the-CFPB.png)

## Objective

The Consumer Financial Protection Bureau is a 21st century agency that implements and enforces Federal consumer financial law and ensures that markets for consumer financial products are fair, transparent, and competitive.

Each week thousands of consumer complaints about financial products and services are sent to respective companies for response. Data from those complaints helps CFPB understand the financial marketplace and protect consumers. This ever-growing CFPB Complaint Database
is publicly avaiable and offers a rich resource for understanding consumer experiences in the financial marketplace.

Our project will provide prediction platform leveraging machine learning to analyze the extensive Consumer Financial Protection Bureau (CFPB) Complaint Database, a publicly
available resource exceeding 4.9 GB in size.

The platform will utilize the machine learning models to classify consumer complaints text into these categories: Debt collection, Consumer Loan, Mortgage, Credit card, Credit reporting, Student loan, Bank account or service, Payday loan, Money transfers, Other financial service, Prepaid card.

## Specifications

CFPB publish complaints after the company responds or after 15 days, whichever comes first. Here's the information provided in the published report. 

<table>
    <tr>
        <th>Field name</th>
        <th>Description</th>
    </tr>
    <tr>
        <th>Date received</th>	
        <th>The date the CFPB received the complaint.</th>
    </tr>
    <tr>
        <th>Product	</th>
        <th>The type of product the consumer identified in the complaint. For example, “Checking or savings account” or “Student loan.”</th>
    </tr>
    <tr>
        <th>Sub-product	</th>
        <th>The type of sub-product the consumer identified in the complaint. For example, “Checking account” or “Private student loan.”</th>
    </tr>
    <tr>
        <th>Issue	</th>
        <th>The issue the consumer identified in the complaint. For example, “Managing an account” or “Struggling to repay your loan.”</th>
    </tr>
    <tr>
        <th>Sub-issue	</th>
        <th>The sub-issue the consumer identified in the complaint. For example, “Deposits and withdrawals” or “Problem lowering your monthly payments.”</th>
    </tr>
    <tr>
        <th>Consumer complaint narrative	</th>
        <th>Consumer complaint narrative is the consumer-submitted description of “what happened” from the complaint. Consumers must opt-in to share their narrative. We will not publish the narrative unless the consumer consents, and consumers can opt-out at any time. The CFPB takes reasonable steps to scrub personal information from each complaint that could be used to identify the consumer.</th>
    </tr>
    <tr>
        <th>Company public response	</th>
        <th>The company’s optional, public-facing response to a consumer’s complaint. Companies can choose to select a response from a pre-set list of options that will be posted on the public database. For example, “Company believes complaint is the result of an isolated error.”</th>
    </tr>
    <tr>
        <th>Company	</th>
        <th>The complaint is about this company. For example, “ABC Bank.”</th>
    </tr>
    <tr>
        <th>State	</th>
        <th>The state of the mailing address provided by the consumer.</th>
    </tr>
    <tr>
        <th>ZIP code	</th>
        <th>The mailing ZIP code provided by the consumer. This field may: i) include the first five digits of a ZIP code; ii) include the first three digits of a ZIP code (if the consumer consented to publication of their complaint narrative); or iii) be blank (if ZIP codes have been submitted with non-numeric values, if there are less than 20,000 people in a given ZIP code, or if the complaint has an address outside of the United States).</th>
    </tr>
    <tr>
        <th>Tags	</th>
        <th>Data that supports easier searching and sorting of complaints submitted by or on behalf of consumers. For example, complaints where the submitter reports the age of the consumer as 62 years or older are tagged “Older American.” Complaints submitted by or on behalf of a servicemember or the spouse or dependent of a servicemember are tagged “Servicemember.” Servicemember includes anyone who is active duty, National Guard, or Reservist, as well as anyone who previously served and is a veteran or retiree.</th>
    </tr>
    <tr>
        <th>Consumer consent provided?	</th>
        <th>Identifies whether the consumer opted in to publish their complaint narrative. We do not publish the narrative unless the consumer consents, and consumers can opt-out at any time.</th>
    </tr>
    <tr>
        <th>Submitted via	</th>
        <th>How the complaint was submitted to the CFPB. For example, “Web” or “Phone.”</th>
    </tr>
    <tr>
        <th>Date sent to company	</th>
        <th> The date the CFPB sent the complaint to the company.</th>
    </tr>
    <tr>
        <th>Company response to consumer	</th>
        <th>This is how the company responded. For example, “Closed with explanation.”</th>
    </tr>
    <tr>
        <th>Timely response?</th>	
        <th>Whether the company gave a timely response. For example, “Yes” or “No.”</th>
    </tr>
    <tr>
        <th>Consumer disputed?	</th>
        <th>Whether the consumer disputed the company’s response.</th>
    </tr>
    <tr>
        <th>Complaint ID	</th>
        <th>The unique identification number for a complaint.</th>
    </tr>
</table>
	

## Workflow

## Data Challenges and Preprocessing Techniques

## Machine Learning
### Unsupervised
### Deep Learning
### NLP

## Execution Pre-requisites 
<ol>
<li>Steps to pull the project in to your local machine.
Please check Git Hub documenatation to find the steps to download this porject in your local machine.


<li> Steps to download the Consumer Complaint Data 
<ol>
    <li>Go to CFPB site (consumerfinance.gov), click on the 'Data and Research' option and select 'Consumer Complaint Database'.</li>
    <li>Select the Date Range(3m), Read 'Only complaints with narratives' and click on Export Data.</li>
    <li>On the Export Complaints pop up, Select 'CSV' for exported file type and Select 'Filtered dataset' to download entries that matches the filtering criteria.</li>
</ol>

<li> Steps to input the Consumer Complaint Data
<ul>
<li>The Consumer Complaint Data downloaded in the above step should be copied to this location Resources\MonthData\ that's inside the Project Folder(ML_CFPB_Complaint_Classification).
</ul>
</ol>

## Data Pre-Processing Stage
Execute the data_analysis notebook inside ML_CFPB_Complaint_Classification\data_preprocessing folder.


## Conclusion



