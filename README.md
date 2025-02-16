# Tailwind CSS Gradient Rendering Issue

This repository demonstrates a bug where a Tailwind CSS linear gradient doesn't render correctly in a React component.  The gradient appears as a solid color instead of a smooth transition between specified colors.

## Bug Report

The issue occurs when using the `bg-gradient-to-r` utility class along with `from-blue-500` and `to-purple-500`.  The expected result is a smooth gradient transition from blue to purple. Instead, a solid color is displayed. This problem is likely due to the way the gradient is applied in the CSS and how it interacts with the component's structure.

## Solution

The solution involves ensuring that the element to which the gradient is applied has sufficient dimensions and that no conflicting styles are overriding the gradient.
