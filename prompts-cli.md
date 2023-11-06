# CLI docs prompts

## Prompt: 

```
based on this template: 

{input docs template}

Make the same with this command:

input CLI command --help

```

## Example

```
based on this template: 

## Create


### Usage

```bash
$ azion create edge-application --name "naruno"
```


### Required flags

#### name

The `--name` flag sets the name of the edge application being created. It's required if the `--in` flag isn't used.

### Optional flags                                                    

#### applicationAcceleration

The `--applicationAcceleration` option displays all relevant fields when listing.

#### filter

The `--browserCacheSettings` option filters items by name.

#### browserCacheSettingsMaximumTtl

The `--browserCacheSettingsMaximumTtl` option sorts the output based on the informed field.

#### cdnCacheSettings

The `--cdnCacheSettings` option returns a page of the list based on the selected field.

#### cdnCacheSettingsMaximumTtl

The `--cdnCacheSettingsMaximumTtl` option defines how many items should be returned per page. By default, it's `10`.

#### deliveryProtocol

The `--deliveryProtocol` option defines the order of the items on the list. The value should be either `asc` or `desc`.

#### originProtocolPolicy

The `--originProtocolPolicy` option defines the order of the items on the list. The value should be either `asc` or `desc`.

#### originType

The `--originType` option defines the order of the items on the list. The value should be either `asc` or `desc`.

#### address

The `--address` option defines the order of the items on the list. The value should be either `asc` or `desc`.

#### in

The `--in` option defines the order of the items on the list. The value should be either `asc` or `desc`.

#### help

The `--help` option displays more information about the `azion create edge-application` action.

#### supported-ciphers

The `--supported-ciphers` option displays more information about the `azion create edge-application` action.

#### websocket

The `--websocket` option displays more information about the `azion create edge-application` action.

#### origin-type

The `--origin-type` option displays more information about the `azion create edge-application` action.

#### origin-protocol-policy

The `--origin-protocol-policy` option displays more information about the `azion create edge-application` action.

#### origin-protocol-policy

The `--origin-protocol-policy` option displays more information about the `azion create edge-application` action.


---

Make the same with this command:

Azion CLI 1.5.1

DESCRIPTION
  Displays all your edge applications in a list

SYNOPSIS
  azion list edge-application [flags]

EXAMPLES
  $ azion list edge-application
  $ azion list edge-application --details
  $ azion list edge-application --page 1 
  $ azion list edge-application --page_size 5
  

LOCAL OPTIONS
      --details         Displays all relevant fields when listing
  -h, --help            Displays more information about the list command
      --page int        Returns a page of the list according to its number (default 1)
      --page_size int   Defines how many items should be returned per page (default 10)
  

GLOBAL OPTIONS
  -c, --config string      Sets the Azion configuration folder for the current command only, without changing persistent settings.
  -d, --debug              Displays log at a debug level
  -l, --log-level string   Displays log at a debug level (default "info")
  -s, --silent             Silences log completely; mostly used for automation purposes
  -t, --token string       Saves a given personal token locally to authorize CLI commands
  -y, --yes                Answers all yes/no interactions automatically with yes
  

LEARN MORE
  
  Use 'azion <command> <subcommand> --help' for more information about a command

```