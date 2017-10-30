# Kill Bill BluePay Plugin

Kill Bill plugin for BluePay.

## Building
`mvn clean install`

## Installing
Copy the JAR (`target/killbill-basecommerce-plugin-<version>.jar`) to the Kill Bill path `/var/lib/killbill/bundles/plugins/java/killbill-basecommerce-plugin/<version>/killbill-basecommerce-plugin-<version>.jar`. This path can change with the `org.killbill.osgi.bundle.install.dir` property.