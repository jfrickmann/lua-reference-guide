# model.getModule\(index\)

Get RF module parameters

`rfProtocol` values:

* -1 OFF
* 0 D16
* 1 D8
* 2 LR12

@status current Introduced in TODO

## Parameters

* `index` \(number\) module index \(0 for internal, 1 for external\)

## Return value

* `nil` requested module does not exist
* `table` module parameters:
  * `rfProtocol` \(number\) protocol index
  * `modelId` \(number\) receiver number
  * `firstChannel` \(number\) start channel \(0 is CH1\)
  * `channelsCount` \(number\) number of channels sent to module
