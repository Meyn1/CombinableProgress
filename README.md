# Combinable Progress<T> C# .Net7
<img align="right" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7d/Microsoft_.NET_logo.svg/225px-Microsoft_.NET_logo.svg.png" alt=".Net7" width="50"/>

A class that inherits from Progress and uses the generic maths function introduced in .Net 7 to calculate the average of all Progress objects when they are numbers.

> Simple calculation and merging of several IPrgress<INumber> objects. 

## Example

In the project, the class Programme is included, which simulates a run of several Progress objects.
The type, the quantity and the maximum number that the progress should return can be exchanged.

```cs

        public static int MaxValue { get; } = 500; // for float 1 or for int 100
        public static int ProgressLength { get; } = 5;

        private static async Task Main(string[] args)
        {
            await Run<byte>(); //  Run<decimal>(); or Run<int>(); or ...
        }
```
![Test](https://user-images.githubusercontent.com/70847870/233017631-04d02668-4dc5-4e18-a16c-2adeaa6c75ed.gif)

## Installation

Download the code and use.


## Development

Want to contribute? Great!😁

## License

MIT
**Free Code**🥳
