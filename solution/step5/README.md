Working python code can be found in folder python.

step5_verification.ipynb reads in the results from step2_boarding_pass.ipynb and step2_id.ipynb and verifies the boarding pass and ID information against the expected values from the manifest. 

In order to do date-of-birth-check as well, I extended the manifest with a date-of-birth-column. The date-of-birth from the id is checked against that value.

In the end, a message is generated for the passenger. The message either confirms the validation and summarizes the flight information or it points the customer to the service desk.
