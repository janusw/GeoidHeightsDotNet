# GeoidHeightsDotNet

Calculate point geoid undulations according to EGM96 at any given WGS84 latitude and longitude by spherical harmonic synthesis.

C# library with all necessary data ported from Fortran code published here:
http://earth-info.nga.mil/GandG/wgs84/gravitymod/egm96/egm96.html

## Usage Example

    using GeoidHeightsDotNet;
    double h = GeoidHeights.undulation(38.6281550, 269.7791550);

## References

* http://earth-info.nga.mil/GandG/wgs84/gravitymod/egm96/egm96.html
* http://stackoverflow.com/questions/22196714/wgs84-geoid-height-altitude-offset-for-external-gps-data-on-ios
* http://gis.stackexchange.com/questions/15744/how-to-get-the-height-according-to-egm96-for-a-point


## License

[MIT](LICENSE)
