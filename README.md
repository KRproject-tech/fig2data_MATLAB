# fig2data_MATLAB
Extract data from the figure file of MATLAB ("*.fig").

"legend" must be eliminated from the figure to load data by fig2data.

## Usage

__[2D case]__ 

[xdata ydata] = fig2data( fig_name);


__[3D case]__ 

[xdata ydata zdata] = fig2data( fig_name);

where


__xdata__ : XData for the figure file. 

__ydata__ : YData for the figure file. 

__zdata__ : ZData for the figure file. 

__fig_name__ : path to the figure file.  

## Demo

"demo.m" load the data from figure files in "./load/" directory, and plot these data.

![untitled](https://user-images.githubusercontent.com/114337358/194798592-4e7d8585-0541-4322-b8bd-443fe1df70e8.png)
__2D case__

![untitled](https://user-images.githubusercontent.com/114337358/194798625-8859ae01-3843-42e5-90cd-f3e3aaac9c2a.png)
__3D case__
