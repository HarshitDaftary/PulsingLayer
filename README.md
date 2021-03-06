# PulsingLayer

Adds a customizable CALayer halo effect to any arbitrary UIView.

Completely written in Swift.

![demo.gif](http://s.kida.io/pulsinglayer_demo.gif)

## How to use

```swift
haloLayer = PulsingLayer(pulseColor: UIColor(white: 1.0, alpha: 1.0))
haloLayer.radius = 90.0
haloLayer.animationDuration = 1
haloLayer.pulseInterval = 0
        
haloView = UIView(frame: CGRectMake(65, 65, 50, 50));
haloLayer.position = CGPointMake(CGRectGetWidth(haloView.frame)/2, CGRectGetHeight(haloView.frame)/2)
haloView.layer.addSublayer(haloLayer)
```

## About

Written from Scratch in Swift.

Inspired by [PulsingHalo](https://github.com/shu223/PulsingHalo).

## License

See [LICENSE.md](LICENSE.md).