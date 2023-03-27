# NMAP-Auto

# NMAP-Auto is a bash script that takes a range of IP address octets and runs an Nmap scan on each IP address within the range, saving the results to a specified output file. It checks command-line arguments for the CIDR notation, start and end octets, and output file. The script also checks if the octets are valid numbers and if the end octet is greater than or equal to the start octet. The script uses a timestamp function and a for loop to iterate over each IP address and output the scan results to the file.
