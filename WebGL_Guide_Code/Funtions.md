### Functions
url => https://developer.mozilla.org/zh-CN/docs/Web/API/WebGLRenderingContext/functionName
1. gl.clearColor(0.0, 0.0, 0.0, 1.0) : 指定填充颜色
2. gl.clear: 填充背景颜色
3. gl.getAttribLocation(gl.program, "a_Position") : 获取变量
4. gl.vertexAttrib3f(a_Position, x, y, 0.0): 赋值3个
5. gl.vertexAttrib3fv(a_Position, [x, y, 0.0]): 数组形式赋值三个值
6. var a_Position = gl.getUniformLocation(gl.program, 'u_FragColor'):  获取uniform变量
7. gl.uniform4f(u_FragColor, rgba[0], rgba[1], rgba[2], rgba[3]): 赋值uniform变量
8. gl.drawArrays(gl.POINTS, start, count);
9. gl.createBuffer() 
10. gl.bindBuffer(type, buffer)
11. gl.vertexAttribPointer(attribute, data, data_type, isNormalize, stride, start)
12. gl.enableVertexAttribArray(attribute)


### Details 
1. 每次绘制完后会清空一次背景


### Vars
1. gl.COLOR_BUFFER_BIT: 缓存的颜色


### keywords
1. vec4: 4个值的矢量
2. attribute: 与顶点有关
3. uniform: 与顶点无关