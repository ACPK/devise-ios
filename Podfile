#
#  Podfile
#
#  Copyright (c) 2014 Netguru Sp. z o.o. All rights reserved.
#

# Pod sources
source 'https://github.com/CocoaPods/Specs.git'

# Initial configuration
platform :ios, '7.1'
inhibit_all_warnings!

# Framework dependencies
pod 'AFNetworking', '~> 2.5'
pod 'Parse', '~> 1.5'

# Unit tests exclusive dependencies
target 'Tests', exclusive: true do link_with 'SaasKit Tests'
  pod 'Kiwi', '~> 2.3'
end
