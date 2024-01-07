# Uncomment the next line to define a global platform for your project

# 1、Flutter本地源码依赖
#flutter_application_path = '../flutter_module'
#load File.join(flutter_application_path, '.ios', 'Flutter', 'podhelper.rb')

platform :ios, '14.0'

target 'FlutterIOSProject' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  use_modular_headers!

#  install_all_flutter_pods(flutter_application_path)

  pod 'RxSwift', '6.6.0'  #https://github.com/ReactiveX/RxSwift
  pod 'RxCocoa', '6.6.0' 
  
   # Auto Layout
  pod 'SnapKit', '~> 5.0'  # https://github.com/SnapKit/SnapKit
  
  
  # 2、Flutter远端依赖编译产物（Frameworks）
  pod 'Flutter', :podspec => './../FlutterModuleSDKPodspec/Flutter.podspec'
  pod 'FlutterModuleSDK', :podspec => './../FlutterModuleSDKPodspec/FlutterModuleSDK.podspec'

  
end


#post_install do |installer|
#   flutter_post_install(installer) if defined?(flutter_post_install)
#end


