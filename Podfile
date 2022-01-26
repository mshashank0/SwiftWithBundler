target 'SwiftWithBundler' do
  platform :ios, '12.0'
  use_frameworks!

  # Wrappers
  pod 'KeychainAccess', '~> 3.1.2'
  pod 'ReachabilitySwift', '~> 4.3.0'

  # Development
  pod 'Reveal-SDK', configurations: ['Debug']

  target 'SwiftWithBundlerTests' do
    inherit! :search_paths
  end

  target 'SwiftWithBundlerUITests' do
    inherit! :search_paths
  end
end
