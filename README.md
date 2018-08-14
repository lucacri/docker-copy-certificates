# docker-copy-certificates

Copy certificates from one folder to another. Use the ENV `DOMAIN_NAME` to set the prefix of the destination files.

Example:

| FROM            | DOMAIN_NAME    | TO                                    |
|-----------------|----------------|---------------------------------------|
| tls.key tls.crt | luca.critel.li | luca.critel.li.key luca.critel.li.crt |
| tls.key tls.crt | file_name      | file_name.key file_name.crt           |