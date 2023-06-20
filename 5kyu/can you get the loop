def loop_size(node):
    nodes = dict()
    position = 0 
    actnode = node
    while actnode != None:
        if actnode not in nodes:
            position += 1
            nodes[actnode] = position - 1
        else:
            return position - nodes[actnode]
        actnode = actnode.next
