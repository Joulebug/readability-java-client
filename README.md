readability-java-client
=======================

An API Client for Readability.com

https://www.readability.com/developers/api


Currently only supporting the Parser API...
If you are interested in expanding this to support other Readability API's, please send a message or Pull Request. 

Usage:

Java:

ReadabilityParserClient client = new ReadabilityParserClient("YOUR_KEY_HERE");

Parser parseResponse = client.parse("http://blog.readability.com/2011/02/step-up-be-heard-readability-ideas/");

parseResponse.getContent();

Scala:

val ReadabilityParserClient client = new ReadabilityParserClient("YOUR_KEY_HERE")

val parseResponse = client.parse("http://blog.readability.com/2011/02/step-up-be-heard-readability-ideas/")

parseResponse.getContent
