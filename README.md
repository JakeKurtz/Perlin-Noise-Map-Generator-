# Map Generation Tools
Just some python scripts to help procedurally generate maps using perlin noise.

## Blend

### Command Line Arguments
```shell
Usage: blend.py [OPTIONS] IMAGE1 IMAGE2 MASK

Options:
  -o TEXT   output file
```
### Example Output

## genNoise

### Command Line Arguments
```shell
Usage: noiseMap.py [OPTIONS] SIZE SCALE

Options:
  -l INT    number of bit levels
  -o TEXT   output file
```
### Example Output

## waterGeometry

### Command Line Arguments
```shell
Usage: waterGeometry.py [OPTIONS] HEIGHT_MAP

Options:
  -o TEXT   output file
```
### Example Output

## genPoints

### Command Line Arguments

Usage: genPoints.py [OPTIONS] MASK LEVELS
```shell
Options:
  -o TEXT                 output file
  -c <INT, INT, INT>...   colors to use for points
  -r INT...               max/min radii
  -sampleRadius INT       sample radius for poisson
  -rejectionSamples INT   number of rejection sample for poisson
```
### Example Output
