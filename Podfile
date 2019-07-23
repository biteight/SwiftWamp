platform :ios, '8.0'

def pods
  inherit! :search_paths
 
  pod 'SwiftyJSON', '~> 5.0.0'
  pod 'Starscream', '~> 3.1.0'
  pod 'CryptoSwift', '~> 1.0.0'
  pod 'SwiftWebSocket', :git => 'https://github.com/tidwall/SwiftWebSocket.git', :tag => 'v2.8.0'
  
end

target 'SwiftWamp' do
  use_frameworks!
  pods

  target 'SwiftWampTests' do
  end

end
