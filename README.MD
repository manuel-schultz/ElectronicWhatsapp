# What is ElectronicWhatsApp?
ElectronicWhatsApp is an app made with electron. All it does is open the webversion of Whatsapp.

# Buildiing a new .deb
After changes are done, in terminal start:
`npm run package-data` and after that `sudo npm run create-deb`.
Dont forget to add rights to the deb file with `sudo chmod 777 *.deb`