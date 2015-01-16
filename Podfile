platform :osx, '10.10'

pod 'Quick',  :git => "https://github.com/Quick/Quick"
pod 'Nimble', :git => "https://github.com/Quick/Nimble"

link_with 'Respect', 'RespectTests'

post_install do |installer|
  installer.project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['FRAMEWORK_SEARCH_PATHS'] = [ '$(PLATFORM_DIR)/Developer/Library/Frameworks' ]
    end
  end
end


