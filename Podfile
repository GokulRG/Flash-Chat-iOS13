platform :ios, '13.0'

target 'Flash Chat iOS13' do
  use_frameworks!

  # Pods for Flash Chat iOS13
  pod 'CLTypingLabel', '~> 0.4.0'
  pod 'IQKeyboardManagerSwift'
  # add pods for desired Firebase products
  pod 'Firebase/Firestore'
  pod 'Firebase/Auth'
  
  post_install do |installer|
      installer.pods_project.build_configurations.each do |config|
          config.build_settings.delete('CODE_SIGNING_ALLOWED')
          config.build_settings.delete('CODE_SIGNING_REQUIRED')
      end
  end
end
