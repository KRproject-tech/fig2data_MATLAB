# fig2data_MATLAB
Extract data from the figure file of MATLAB ("*.fig").

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
