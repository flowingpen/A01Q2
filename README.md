A01Q2
=====
void delete(struct node *ptr)
{
struct node *temp;
temp=ptr->next;
ptr->data=temp->data;
ptr->next=temp->next;
free(temp);
}
