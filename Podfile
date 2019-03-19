platform :ios, '8.0'

def pods
  inherit! :search_paths
  pod 'SwiftyJSON'
  pod 'Starscream'
  pod 'CryptoSwift'
  pod 'SwiftWebSocket', :git => 'https://github.com/biteight/SwiftWebSocket.git'
end

target 'SwiftWamp' do
  use_frameworks!
  pods

  target 'SwiftWampTests' do
  end

end
