download all the .jar files to "nxsd" folder (any foldername should be fine)
      1. bpm-infra.jar
      2. mail.jar
      3. test-translator.jar
      4. xml.jar
      5. xmlparserv2.jar

run the below command providing correct directory path

java -cp c:\nxsd\* xlator.util.Translate -inbound -schema c:\nxsd\sample.xsd -root <root-element-name> -input c:\nxsd\input.dat -output c:\nxsd\output.xml

You will get the tested output XML file if the Input files follow the schema.
