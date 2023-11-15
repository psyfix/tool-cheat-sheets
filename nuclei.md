Nuclei Cheat Sheet

# Identify web technologies
nuclei -u https://example.com -as 

# Specify a URL to test
nuclei -u https://example.com -t ~/nuclei-templates/

# Specify a single target to test
nuclei -t https://example.com -t ~/nuclei-templates/

# Specify the number of concurrent threads to use
nuclei -c 10 -t https://example.com -t ~/nuclei-templates/

# Customize the output format of the Nuclei report
nuclei -o output.txt -t https://example.com -t ~/nuclei-templates/
