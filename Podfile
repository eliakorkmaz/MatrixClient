# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'MatrixClient' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for MatrixClient
  pod 'OLMKit'
  pod 'Realm'
#  pod 'MatrixSDK', :path => '../matrix-ios-sdk'
  pod 'MatrixSDK', :git => 'https://github.com/aapierce0/matrix-ios-sdk.git', :commit => '282dcdd5de79f6ebd963222b8a2c2416b58ca3fd'

  target 'MatrixClientTests' do
    inherit! :search_paths
    # Pods for testing
  end

end

