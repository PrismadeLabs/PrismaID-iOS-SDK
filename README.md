## PrismaID iOS SDK

### Create Podfile
  
  ```bash
  pod init
  ```
 
### Edit Podfile

```ruby
source 'https://github.com/CocoaPods/Specs.git'
source 'https://github.com/PrismadeLabs/Specs.git'

# Uncomment the next line to define a global platform for your project
platform :ios, '12.2'

target 'iossdkexample' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for iossdkexample
  pod 'PrismaID'

end
```

### Install Pods

```bash
pod install
```

### Update Pods

```bash
pod update PrismaID
```
