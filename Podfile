source 'https://github.com/CocoaPods/Specs.git'

platform :ios, "7.0"

inhibit_all_warnings!

def shared_code
    pod 'RSTWebViewController', :git => 'https://github.com/rileytestut/RSTWebViewController-Legacy.git'
    pod "AFNetworking", "~> 2.4"
    pod "PSPDFTextView", :git => 'https://github.com/steipete/PSPDFTextView.git'
    pod "Dropbox-iOS-SDK", "~> 1.3.0"
    pod "CrashlyticsFramework", "~> 2.1.0"
end

target 'GBA4iOS' do
    shared_code
end

target 'GBA4iOS-Simulator' do
    shared_code
end
