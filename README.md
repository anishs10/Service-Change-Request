# Service-Change-Request

Today, I considered writing a content that covers essential points for aspiring L1 Oracle DBAs, based on my personal experiences. If you have any additional topics you think should be included in the L1 Oracle DBA category, please share your suggestions in the comments, and I will gladly incorporate them. 

To start, I will create a guide on how to submit a Service Request (SR) in My Oracle Support.

There are various reasons why we might need to connect with Global Oracle Support, depending on the client's needs. Some clients may even monitor Service Requests (SRs) and ask for explanations, although I haven't encountered such clients yet. Let's keep that discussion for another time.

Typically, Oracle DBAs are responsible for raising a Technical Service Request (SR), whether it's for an ongoing issue that needs Oracle’s attention or for specific error codes like ORA-600 or ORA-4013, etc.

**Logging into Oracle Support**

While the login page and graphics may have changed over time, the process remains the same:

1. Go to the Oracle Support website: (https://support.oracle.com).
2. Click on "Login to My Oracle Support."

<img width="940" alt="image" src="https://github.com/anishs10/Service-Change-Request/assets/48911049/820be53e-c3c1-43a1-adda-2c67d788dbef">

<img width="370" alt="image" src="https://github.com/anishs10/Service-Change-Request/assets/48911049/fc86d5de-7f5d-4a62-b4f3-9c3a9fda0fee">

<img width="355" alt="image" src="https://github.com/anishs10/Service-Change-Request/assets/48911049/ca8da7fb-bfdf-48bb-8e6f-f30d7bdafbe4">

3. Once you have successfully logged in to My Oracle Support, you will be directed to the Dashboard page. From there, find and click on "Service Requests" as shown in the image below.

<img width="723" alt="image" src="https://github.com/anishs10/Service-Change-Request/assets/48911049/1d1eaa7f-d637-407f-8311-07ace5eed81c">

4. Click on "Create Technical SR," as illustrated in the image below.

<img width="626" alt="image" src="https://github.com/anishs10/Service-Change-Request/assets/48911049/7ec7e9d2-8259-4b99-b78d-a131b13cb8e4">

<img width="736" alt="image" src="https://github.com/anishs10/Service-Change-Request/assets/48911049/b4c73035-0fad-4c6a-8345-b1983e0fa7a3">

4. If you're raising a request for Oracle Database Enterprise Edition, select that as the product. For Oracle GoldenGate issues, choose Oracle GoldenGate.

Next, select the appropriate product version based on your database version, such as 19.11, 19.9, or 19.7.

To identify your operating system platform, use the `uname` command. For instance, if you're using Sun Solaris, select Sun Solaris and the corresponding base version like 5.11 or 5.10.

If the system is owned by Oracle, such as an Exadata machine or ExaCloud, select "Yes."

Choose the problem type from the dropdown menu. Options may include Cluster installation/patching/upgrade, Database installation/patching/upgrade (single instance), ORA-600, etc.

Typically, you'll have one Support Identifier. However, if you have multiple contracts with Oracle, you may have several Support Identifiers listed. This helps Oracle SR Engineers determine if you have support for a specific issue. For instance, if you have extended support for Oracle 11g, this information will be associated with your Support Identifier.

After selecting the problem type, the next tab will ask specific questions related to that issue. For example, if you are raising a performance issue, you might be asked about the incident time, whether the issue is ongoing or resolved, and other relevant details. Once you provide this information, click on "Next" to proceed.

![image](https://github.com/anishs10/Service-Change-Request/assets/48911049/1528d428-a325-4968-b6cf-20b5bb015c51)

On the subsequent tab, you'll be prompted to upload any relevant logs you've collected regarding the issue. This may include logs such as TFA (Trace File Analyzer) or any other supporting logs that could assist in diagnosing the problem. Once you've uploaded the necessary logs, click on "Next" to continue

Proceed by entering your contact details. This step involves providing accurate and up-to-date information including your name, email address, phone number, and any other relevant contact details.

![image](https://github.com/anishs10/Service-Change-Request/assets/48911049/a80ee178-91b6-418f-b0bc-acca4f823bfe)

Once you've reviewed all the details and ensured everything is accurate, proceed by clicking on "Submit." This will finalize the submission of your service request to Oracle Support.

Hope it helped !! :)
