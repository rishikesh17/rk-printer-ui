# rk-printer
 
 
Add below code in Config.TargetModel

[1] = { --Printer
		models = {
			"prop_printer_01"
		},
		options = {
			{
			event = "qb-printer:client:useprinter",
			icon = "fa-solid fa-print",
			label = "Use Printer",			
			type = 'client',
			},
		},
	},
 
 These are the new UI
 ![Printer1](https://user-images.githubusercontent.com/95628640/194777352-6ed33a33-2b87-4774-85bc-d8675cf17d90.png)
![Printer2](https://user-images.githubusercontent.com/95628640/194777350-203ff7bb-a335-4c63-89c9-7f0694d4f160.png)
