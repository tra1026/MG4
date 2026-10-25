# MG4
## Devlog
In Start(), _timer is set to _switchSpeed to begin the countdown. In Update(), the script moves the food up or down using transform.Translate and Time.deltaTime, based on the value of _up. It subtracts Time.deltaTime from _timer each frame. When _timer reaches zero, it resets the timer and switches _up to the opposite value, so the food changes direction. This repeats to make the food float up and down.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)