# NTMLspray
Is password sprayer to attack AD-connected NTLM endpoints.

`
python ntlm_passwordspray.py -u <usernames_wordlist> -f <theDomainName> -p <password> -a <vuln_url>.
`
We provide the following values for each of the parameters:

    <usernames_wordlist> - Textfile containing our usernames.
    <theDomainName> - Fully qualified domain name associated with the organisation that we are attacking - "test.google.com"
    <password> - The password we want to use for our spraying attack - "test123"
    <vuln_url> - The URL of the application that supports Windows Authentication - "http://lol.test.google.com"
