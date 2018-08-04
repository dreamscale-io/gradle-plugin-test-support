[![Build Status](https://travis-ci.org/dreamscale-io/gradle-plugin-test-support.svg?branch=master)](https://travis-ci.org/dreamscale-io/gradle-plugin-test-support)

# Gradle Plugin Test Support library

Shared code to support testing gradle plugins.

# Publishing to Bintray

Make sure you have a bintray account and are a member of the [DreamScale organization](https://bintray.com/dreamscale/organization/edit)

Open your [user profile](https://bintray.com/profile/edit/organizations) and retrieve your API Key

Execute bintray upload `gw bintrayUpload -Pbintray.user=<bintray user> -Pbintray.apiKey=<api key>`

Open the DreamScale [gradle-plugin-test-support](https://bintray.com/dreamscale/maven-public/org.dreamscale%3Agradle-plugin-test-support) package and
click the [Publish](https://bintray.com/dreamscale/maven-public/org.dreamscale%3Agradle-plugin-test-support/publish) link