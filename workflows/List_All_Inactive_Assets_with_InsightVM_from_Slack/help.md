# Description

Quickly look up inactive assets in [Rapid7 InsightVM](https://www.rapid7.com/products/insightvm/) using a slack command. This workflow helps teams share vulnerability intelligence through shared Slack channels.

# Key Features

* Look up inactive assets in InsightVM using a slack command

# Requirements

* [Rapid7 InsightVM](https://www.rapid7.com/products/insightvm/)
* [Slack](https://insightconnect.help.rapid7.com/docs/configure-slack-for-chatops)

# Documentation

## Setup

Import the workflow from the Rapid7 Extension Library and proceed through the Import Workflow wizard in InsightConnect. Import plugins, create or select connections, and rename the workflow as a part of the Import Workflow wizard as necessary.

Once the workflow has been imported,

Update the first step with the channel name to suit your Slack environment! by editing the input with the preset text of `change_me` to match the channel to monitor.

After import, activate the workflow in order to trigger it.

## Usage

*This workflow will trigger in any direct messages to your Chatbot **or** any message in a channel directed @ your Chatbot. Note the Chatbot must be in the channel in order to trigger the workflow this way.*

To run the workflow, send a direct message to your InsightConnect Slack Chatbot or @ your Chatbot in a public channel starting with the command `list-inactive`.

For example, in a direct message to your Chatbot:
* `@Rapid7 InsightConnect list-inactive`

## Technical Details

Plugins utilized by workflow:

|Plugin|Version|Count|
|----|----|--------|
|Rapid7 Vulnerability & Exploit Database|2.0.3|3|
|Type Converter|1.5.1|2|
|Basename|1.0.1|2|
|URL Extractor|1.0.3|1|

## Troubleshooting

_There is no troubleshooting information at this time_

# Version History

* 1.0.0 - Initial workflow

# Links

## References

* [Rapid7 InsightVM](https://www.rapid7.com/products/insightvm/)
* [Slack](https://slack.com)