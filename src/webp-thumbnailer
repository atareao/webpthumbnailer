#!/bin/bash

file_in="$1"
file_out="$2"
size="$3"
if [[ $size == "" ]]; then
	size=128
fi
convert -thumbnail $size $file_in png:$file_out
