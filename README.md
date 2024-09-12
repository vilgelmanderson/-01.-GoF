class ProgramNodeBuilder:
    def __init__(self):
        self._node = None

    def new_variable(self, variable_name):
        pass

    def new_assignment(self, variable, expression):
        pass

    def new_return_statement(self, value):
        pass

    def new_condition(self, condition, true_part, false_part):
        pass

    def get_root_node(self):
        return self._node
