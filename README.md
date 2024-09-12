class ProgramNodeBuilder:
    def __init__(self):
        self._node = None

    def new_variable(self, variable_name):
        # Логика создания новой переменной
        pass

    def new_assignment(self, variable, expression):
        # Логика создания нового присваивания
        pass

    def new_return_statement(self, value):
        # Логика создания return statement
        pass

    def new_condition(self, condition, true_part, false_part):
        # Логика создания условного выражения
        pass

    def get_root_node(self):
        # Возвращает корневой узел
        return self._node
