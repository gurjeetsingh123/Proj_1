
Proj_1- File distributor from a source location to multiple destination location

"""
Created on Tue Sep  4 09:07:29 2018

@author: Gurjeet Singh
"""
Runs a sniffer on user provided source folder to check if there are any files in the folder. If any file is found then it distributes these fiels to user provided destination location.
- Sniffing of the source folder for distributing newly added files is supported
- Defining Multiple destination locations are supported. 
- Deleting the original file after distibuting the file is supported
- Retries for failed files is supported and configurable
- Source folder sniffing time is configurable. Default is every 10 secs. 
