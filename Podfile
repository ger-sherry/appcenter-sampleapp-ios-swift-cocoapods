platform :ios, '12.4'

target 'sampleapp-ios-swift' do
  use_frameworks!

  pod 'AppCenter'
  pod 'AppCenter/Analytics'
  pod 'AppCenter/Crashes'
  pod 'sqlite3', '3.25.3', inhibit_warnings: true
  pod 'sqlite3/fts'
  pod 'sqlite3/fts5'
  pod 'FFmpeg', '2.8.3'
  pod 'freetype', '2.6.4'
  pod 'ImageMagick', '6.8.8-9'

  target 'sampleapp-ios-swiftUITests' do
    inherit! :search_paths
    # Pods for testing
    pod 'VSMobileCenterExtensions'
  end

end
