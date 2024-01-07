# Uncomment the next line to define a global platform for your project

flutter_application_path = '../flutter_module'
load File.join(flutter_application_path, '.ios', 'Flutter', 'podhelper.rb')

platform :ios, '14.0'

target 'FlutterIOSProject' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  use_modular_headers!

  install_all_flutter_pods(flutter_application_path)

  pod 'RxSwift', '6.6.0'  #https://github.com/ReactiveX/RxSwift
  pod 'RxCocoa', '6.6.0' 
  
   # Auto Layout
  pod 'SnapKit', '~> 5.0'  # https://github.com/SnapKit/SnapKit
  
end


post_install do |installer|
   flutter_post_install(installer) if defined?(flutter_post_install)
end


