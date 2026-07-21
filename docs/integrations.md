# Website Integrations

## Objective

The objective of this stage was to connect the Allforliz website with external tools and internal workflows used by the company.

These integrations helped improve lead collection, reduce manual work and create a more organized process for handling website submissions.

## Main Integrations

The website was connected with the following tools:

- Elfsight
- n8n
- Webhooks
- Website forms
- Internal databases
- Customer service chatbot

## Get Your Free Estimate Form

The Get Your Free Estimate form was created to collect information from potential customers interested in painting and remodeling services.

The form was designed to collect information such as:

- Customer name
- Phone number
- Email address
- Project address
- Requested service
- Project description
- Preferred project timeline
- Preferred contact method
- Additional information

The form was embedded into the website using Elfsight.

## Work With Us Form

The Work With Us form was created for workers, subcontractors and professionals interested in working with the company.

The form was designed to collect information such as:

- Full name
- Phone number
- Email address
- Area of experience
- Professional background
- Availability
- Additional information

The form was also integrated into the website through Elfsight.

## Elfsight Integration

Elfsight was used to create and embed interactive forms into the website.

The integration allowed the forms to be displayed directly on the website while sending submitted information to external automation workflows.

The main benefits included:

- Faster form implementation
- Responsive form design
- Easier maintenance
- Integration with automation tools
- Better user experience
- Centralized lead collection

## Webhook Integration

When a visitor submits a form, the data is sent to a webhook.

The webhook acts as the connection between the website form and the n8n workflow.

A simplified flow is shown below:

```text
Website Visitor
      |
      v
Elfsight Form
      |
      v
Webhook
      |
      v
n8n Workflow
      |
      v
Data Processing
      |
      v
Internal Database
```

## n8n Workflow Integration

n8n was used to receive, process and organize data submitted through the website forms.

The workflow was responsible for tasks such as:

- Receiving form data
- Reading the webhook payload
- Validating required fields
- Organizing submitted information
- Transforming data when necessary
- Sending information to the correct database
- Creating structured lead records
- Supporting internal follow-up processes

## Data Processing

The form submission data required organization before being stored.

The processing stage included:

- Field mapping
- Data normalization
- Required field validation
- Contact information formatting
- Service categorization
- Source identification
- Status assignment

This helped create consistent records inside the company's internal systems.

## Customer Service Chatbot

A chatbot was implemented on the website to create an additional communication channel for visitors.

The chatbot was designed to help customers:

- Ask initial questions
- Learn about available services
- Contact the company
- Request more information
- Begin the estimate request process

The chatbot contributed to a more accessible customer experience, especially when visitors needed assistance outside regular business hours.

## Integration Architecture

The website integration architecture can be represented as:

```text
Allforliz Website
      |
      |------ Get Your Free Estimate Form
      |
      |------ Work With Us Form
      |
      |------ Customer Service Chatbot
      |
      v
External Integration Layer
      |
      |------ Elfsight
      |
      |------ Webhooks
      |
      v
Automation Layer
      |
      |------ n8n
      |
      v
Internal Systems
      |
      |------ Lead Database
      |
      |------ Applicant Database
      |
      |------ Follow-Up Process
```

## Main Challenges

The main challenges included:

- Mapping form fields correctly
- Connecting third-party tools
- Maintaining consistent data formats
- Preventing missing information
- Testing webhook submissions
- Organizing different types of submissions
- Avoiding duplicate or incomplete records
- Protecting private company information

## Testing Process

The integrations were tested by submitting sample information through the website forms.

The testing process included:

- Verifying form submission
- Confirming webhook reception
- Reviewing the received data
- Checking field mapping
- Confirming database record creation
- Testing different types of responses
- Identifying missing or incorrect fields
- Correcting workflow errors

## Results

The integrations contributed to:

- Reduced manual data entry
- Faster lead registration
- More consistent customer information
- Better organization of submissions
- Improved communication between the website and internal systems
- Better support for customer follow-up
- More efficient handling of job applications
- Additional customer support through the chatbot

## Security and Privacy

The repository will not include:

- Real webhook URLs
- API keys
- Access tokens
- Customer information
- Applicant information
- Internal database identifiers
- Private company credentials

All examples will use fictional, anonymized or public information.

## Evidence

Screenshots and diagrams related to the integrations will be added to:

```text
assets/screenshots/integrations/
assets/diagrams/
```
