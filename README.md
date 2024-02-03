Simple jupyter notebook, that does SEC edgar analysis for you. 


## Getting filings from the SEC's EDGAR database and turning it into enterprise leads

1. Process the data into one large dataset. First we'll download everything and then convert it to bianary to speed up the processing times
2. Narrow the companies down to your ICP (we'll use the SIC number) -- figure out the relative size of each company (we'll do total assets)
3. get the latest filing & chunk the data into smaller sections. use gpt-3.5 to do this. Save the chuck position that has the data most relevent to you. 
4. Pass the best material to gpt-4 for find the companies where we have the best value prop. 
5. Retreive linkedIn info & good luck to you.

This downloading and processing time's should be about an hour

## To make this work
1. Have the packages from the import section installed
2. go through the document and rewrite each path for your system and where you want the data imported and exported
3. fill out the code and prompt section 

## WARNING 

It will cost ~ $.20 - .60 for each gpt-3 extraction cycle

It will cost ~ $.00 - .40 for each gpt-4 output. 

If you do this with every SEC filed company it will cost ~$500-2600. Depending on how the gpt-3.5 model is filtering relevence. 

## If you are changing sic codes

start at where the first CSV is being compiled, I put a "start here" text box above it, and go through the next cells sequentially. 

## Last note

My Jupyter Notebook has more memory allocated to it, if you're are having issues with the first CSV output, message me and i'll walk you through it

GL
