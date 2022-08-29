We received quite a few emails from readers asking, "Well, if that's so easy to do, can't you provide us with a real example?" That was not the plan (since the idea is to write the renderer step-by-step) but we wrote a minimalistic ray-tracer which is about 300 hundred lines in about a couple of hours. Although we are not necessarily proud of that performance, we just wanted to show that when one knows these techniques well, implementing them is not difficult. The source code is available for download. We did not and will not spend time commenting on this program. It was written fairly quickly so sure there is room for improvement. In this version of the raytracer, we made the light visible (it's a sphere) so its reflection would appear in the reflective balls. When glass spheres are transparent (white) it is sometimes hard to see them, so in our example, we tinted them slightly (red). In the real world, clear glass is not necessarily visible. It depends on the environment (have you ever walked into a door made out of glass?). Note that the resulting image is not completely accurate. The shadow under the transparent red sphere should not be completely opaque. We will learn in future lessons how we can easily correct this visual inaccuracy. We also implemented other features such as a fake fresnel (using the facing ratio) and refraction. All these things will be studied later so do not worry if you don't understand them clearly at the moment. At least, you now have a small program to play with.