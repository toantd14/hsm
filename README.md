# hsm


```bash
java -jar .\target\smartsign-tool-1.0.0-standalone.jar --vendor oneoffice --file files/doc_0.pdf --image files/signature.jpeg --page 1 --position 85,361,235,261 --output files/signed_doc_0.pdf --key files/cert.p12 --passwd oKLxVP
java -jar .\target\smartsign-tool-1.0.0-standalone.jar --vendor oneoffice --file files/doc_90.pdf --image files/signature.jpeg --page 1 --position 430,150,530,200 --output files/signed_doc_90.pdf --key files/cert.p12 --passwd oKLxVP

java -jar .\target\smartsign-tool-1.0.0-standalone.jar --vendor pvfco --file files/doc_0.pdf --image files/signature.jpeg --page 1 --position 85,361,235,261 --output files/signed_doc_0.pdf --username dkphuong --passwd 123456
java -jar .\target\smartsign-tool-1.0.0-standalone.jar --vendor pvfco --file files/doc_90.pdf --image files/signature.jpeg --page 1 --position 430,150,530,200 --output files/signed_doc_90.pdf --username dkphuong --passwd 123456
```