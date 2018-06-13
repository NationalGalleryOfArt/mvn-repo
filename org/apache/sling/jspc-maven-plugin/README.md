# Project Title

This is an update on the Apache Sling JscpC Maven Plugin version 2.1.0 https://sling.apache.org/components/jspc-maven-plugin/index.html
Changes are for java 8 support, including dependendencies,  code and java version enforcer update.  

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

### Installing

To use this plugin, first add this nga mvn repository to your pom.xml:

                <pluginRepository>
                    <id>nga-mvn-repo</id>
                    <name>National Gallery Of Art Public Maven Repository</name>
                    <url>https://raw.github.com/NationalGalleryOfArt/mvn-repo/public</url>
                    <releases>
                        <enabled>true</enabled>
                        <updatePolicy>never</updatePolicy>
                    </releases>
                    <snapshots>
                        <enabled>false</enabled>
                    </snapshots>
                </pluginRepository>
                
Then include this plugin as:

                <plugin>
                    <groupId>org.apache.sling</groupId>
                    <artifactId>jspc-maven-plugin</artifactId>
                    <version>2.1.0-nga</version>
                </plugin>

## Built With

* [Maven](https://maven.apache.org/) - Dependency Management

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

## License

This project is licensed under the Apache License - see the original license here https://sling.apache.org/components/jspc-maven-plugin/index.html




