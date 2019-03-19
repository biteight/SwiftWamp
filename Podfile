platform :ios, '8.0'

def pods
  inherit! :search_paths
  pod 'SwiftyJSON'
  pod 'Starscream'
  pod 'CryptoSwift'
  pod 'SwiftWebSocket', :git => 'https://github.com/biteight/SwiftWebSocket.git', :commit => 'd65d1c7e8e43bf56cca980b15653c836f2e1a56e'
end

target 'SwiftWamp' do
  use_frameworks!
  pods

  target 'SwiftWampTests' do
  end

end
