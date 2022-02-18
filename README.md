Usage example:
>>    file_name = "example-cert.pem"  
>>    CN = 'localhost'  
    O = 'XYZ Widgets Inc'  
    OU = 'IT Department'  
    L = 'Seattle'  
    ST = 'Washington'  
    C = 'US'  
    emailAddress = 'e@example.com'  
> 
    os.chdir(sys.path[0])
    create_self_signed_cert(file_name, CN, O, OU, L, ST, C, emailAddress);
    sys.exit(0)
