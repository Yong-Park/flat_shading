# flat_shading

r = Render() /n
scale_factor = (6,6,16)
translate_factor = (512,512,0)
r.glCreateWindow(1024,1024)

r.lightPosition(2,-3,-1)
r.render_obj('./modelos/frost.obj',scale_factor,translate_factor)
r.glFinish()
