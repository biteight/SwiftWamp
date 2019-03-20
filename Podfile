platform :ios, '8.0'

def pods
  inherit! :search_paths
 
  pod 'SwiftyJSON', '~> 4.2.0'
  pod 'Starscream', '~> 3.0.2'
  pod 'CryptoSwift', '~> 0.14.0'
  pod 'SwiftWebSocket', :git => 'https://github.com/biteight/SwiftWebSocket.git'

end

target 'SwiftWamp' do
  use_frameworks!
  pods

  target 'SwiftWampTests' do
  end

end
